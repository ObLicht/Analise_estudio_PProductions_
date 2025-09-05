
 # Analise-estudio-_PProductions_
Esse projeto busca realizar uma EDA com Python e avaliar uma possível nota IMDB.

## Primeiras Impressões

Observei que o documento apresentava mais de 900 linhas com diferentes títulos. Diante disso, fui para o ponto que achei primordial, dentre os títulos, quais possuíam as maiores avaliações.

- The Godfather => **9.2 de IMDB**

> O IMDB é a base de dados que fornece informações filmes, séries e semelhantes. Considerado a fonte mais confiável e mais popular do mundo. *Dado:(https://www.imdb.com/pt/)*

Esse filme em específico consiste em uma guerra por poder, com tramas de assassinatos e de mafiosos. Ademais, o que tornou o filme tão aclamado ao público, foi sua narrativa que explora temas complexos e características autênticas. 

Outro ponto importante é seu ano de lançamento: **1972**, o que leva a questionar se seu público ainda seria o "mesmo", já que teoricamente, as pessoas que assistiram aquele filme, são 53 anos mais velhas.

- The Dark Knight => **9.0**

O segundo lugar é relativamente mais atual (**2008**), Batman pode ser visto como um herói que combate o crime diretamente, esse tema tem sido bem atrativo ao público da "geração z", mas com característimas semelhantes ao primeiro lugar. Pode-se dizer que o que diferencia os dois é uma roupa, ambos apresentam temas críticos, lutas, assasinatos, histórias que prendem. Dito isso, o maior abismo de suas produções, é que no segundo, o personagem principal usa capa para se disfarçar.

## Ainda no top 10

Temos os dois filmes de **The Lord of the Rings**, podem ser considerados mais recentes por terem sido produzidos após os anos **2000**, apresenta de forma mais fantasiosa temas com críticas, apesar de apresentar batalhas, o teor fantasioso ameniza o *"peso"* da mensagem do filme, resistência e liberdade.

### Qual filme você recomendaria para uma pessoa que você não conhece?

- Eu já assisti os filmes citados acima, apesar de amar a saga do senhor dos anéis, acredito que **The Knight Dark** prenda um pouco mais a realidade. Mas caso fosse alguém que gostasse de *fugir da realidade*, indicaria **The Lord of the Rings**.

### Quais são os principais fatores que estão relacionados com alta expectativa de faturamento de um filme? 
- Os gêneros
- Temas abordados, foram o ponto chave.
- O público.

A imagem apresentada no site a seguir, demonstra que a maior parte da população se concetra entre jovens e adultos, o que leva a priorizar esse grupo de pessoas. *Dado: (https://brasilescola.uol.com.br/brasil/piramide-etaria-populacao-brasileira.htm)*

### Quais insights podem ser tirados com a coluna Overview? É possível inferir o gênero do filme a partir dessa coluna?
- É possível deduzir quais gêneros se aplicam, mas é muito simples para tratar com precisão.

### Explique como você faria a previsão da nota do imdb a partir dos dados. Quais variáveis e/ou suas transformações você utilizou e por quê? Qual tipo de problema estamos resolvendo (regressão, classificação)? Qual modelo melhor se aproxima dos dados e quais seus prós e contras? Qual medida de performance do modelo foi escolhida e por quê?
- Bom, primeiramente veria se atendeu a demanda do público, levando em conta o que é atrativo a essa parcela de pessoas no tempo de publicação, e como se comportou em relação a meta desejada. Caso cumpra esses pontos de forma positiva, veriam-se as demais variáveis.  

### Supondo um filme com as seguintes características:

`{'Series_Title': 'The Shawshank Redemption',
 'Released_Year': '1994',
 'Certificate': 'A',
 'Runtime': '142 min',
 'Genre': 'Drama',
 'Overview': 'Two imprisoned men bond over a number of years, finding solace and eventual redemption through acts of common decency.',
 'Meta_score': 80.0,
 'Director': 'Frank Darabont',
 'Star1': 'Tim Robbins',
 'Star2': 'Morgan Freeman',
 'Star3': 'Bob Gunton',
 'Star4': 'William Sadler',
 'No_of_Votes': 2343110,
 'Gross': '28,341,469'}`

- A nota seria considerada alta, pelo número de votos, mas denpederia exatamente dessas notas públicas, o que pode variar, o mais provável seria um **8.5** para **9.0**

## Como rodar

- Clone o repositóro, crie um ambiente virtual, instale as bibliotecas necessárias e o Jupyter notebook.