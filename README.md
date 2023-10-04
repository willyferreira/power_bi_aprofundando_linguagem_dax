## Curso Alura | Power BI: Aprofundando na linguagem DAX | (Curso Alura)

O curso teve como ensinamentos os seguintes assuntos:

- Criação de colunas calculadas e medidas
- Compreendimento de como o contexto é afetado pelos filtros
- Utilização da função **CALCULATE**
- Combinação da função **CALCULATE** para obter medidas elaboradas
- Como a função **CALCULATE** sobrescreve ou agrega com outros filtros

Nesse repositório, há também um notebook em Python onde realizei a análise exploratória dos datasets como forma de conhecer melhor a base, promover o tratamento dos dados para simular situações reais enfrentadas no mercado de trabalho e gerar algumas visualizações simples.

### Modelo de Dados

![Modelo de dados](https://github.com/willyferreira/power_bi_aprofundando_linguagem_dax/blob/c122cbbc620444faf9005ef08e54b15588b2651d/images/relacionamentos.png)


### Funções utilizadas

Para auxílio na criação de medidas, foi utilizada a função **RELATED** que faz a "busca" de uma informação em uma outra tabela. No exemplo abaixo, buscamos a informação sobre a Categoria do livro na tabela *registro_livros_marketing* e a incluimos na tabela *registro_notas_logistica* por meio da criação de uma coluna calculada.

```
#Categoria = RELATED(registro_livros_marketing[Categoria])

