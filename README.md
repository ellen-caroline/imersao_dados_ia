<img width=100% alt="blue_waves_head" src="https://capsule-render.vercel.app/api?type=waving&color=2132a6&height=120&section=header"/>

<h3 align="center"> Imersão Dados: Análises com Inteligência Artificial - Alura </h3>

##
<div align="center">
  <img align="center" width="70" alt="chatGPT-badge" src="https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white" target="_blank">
  <img align="center" width="70" alt="kaggle-badge" src="https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white" target="_blank"><br>
</div>
<div style="padding: 150">
  <p align="center">
    <img align="center" width="250" alt="mergulhador_fundo_oceano" target="_blank" src="/images/diver.png">
  </p>
</div>

##
  
### 📁 Descrição do projeto

   Esse projeto foi desenvolvido durante a [`Imersão Dados_IA`](https://www.alura.com.br/imersao-dados-ia), disponibilizada pela [`Alura`](https://www.alura.com.br/), com o objetivo de introduzir a habilidade e técnicas de análise de dados a pessoas interessadas por tecnologia, afim de desenvolver e aprimorar habilidades em Excel, Python e ferramentas de IA. Dentre algumas tecnologias apresentadas pelos instrutores, estão: ChatGPT, Google Sheets, Google Colab e Bing.AI. Foi uma imersão que pontuou sobre o impacto significativo que as inteligências artificiais estão causando no mundo e as diversas maneiras de aplicá-las.
##
### 🤿 Aula 1: Análise exploratória da base de dados e chatGPT
#### Introdução 
  A primeira aula da imersão apresenta o Kaggle como plataforma e utiliza uma base de dados de compras da Amazon para realizar uma análise exploratória. Além disso, o ChatGPT é introduzido como uma ferramenta auxiliar na geração de fórmulas básicas no Google Sheets. Foi disponibilizado uma base de dados [`"Amazon Sales Dataset"`](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset) (traduzido para o português, Vendas da Amazon Dataset), do Kaggle, com o intuito de acompanhar e realizar as atividades propostas durante a aula. 
<br>
#### Sobre a base de dados "Amazon Sales Dataset"
  Na planilha de dados da Amazon, havia as seguintes informações: 
  - product_id: ID do produto
  - product_name: Nome do produto
  - category: Categoria do produto
  - actual_price: Valor do produto com desconto, em rúpias indianas
  - product_price: Valor do produto com valor cheio, em rúpias indianas
  - rating: Valor de 0 a 5 avaliando o produto
  - rating_count: Quantidade de pessoas que avaliaram o produto
  - about_product: Descrição do produto
  - product_link: Link do produto na loja da Amazon

  Posteriormente, ao longo das aulas, foi adicionado outras colunas, sendo elas:
  - category_geral: Categoria principal do produto
  - subcategory: Subcategoria do produto
  - actual_price_real: Valor do produto com desconto, em reais
  - review_title: Título da avaliação
  - review_content: Conteúdo/descrição da avaliação
  - review_title_ptbr: Título da avaliação em português
  - review_content_ptbr: Conteúdo/descrição da avaliação em português
  - summary_review: Resumo da avaliação
  - feeling: Sentimento principal da avaliação

#### Desafios propostos
  -	Adicionar a formatação condicional de cores à coluna de porcentagens (no dataset "Amazon Sales Dataset")
  -	Realizar uma análise exploratória e aplicar as mesmas técnicas utilizando o ChatGPT a uma nova base de dados do Kaggle: [`Top 1000 IMDb Movies Dataset`](https://www.kaggle.com/datasets/inductiveanks/top-1000-imdb-movies-dataset) 
##
### 🤿 Aula 2: Manipule planilhas e crie gráficos com ajuda da IA
#### Introdução
  Na segunda aula da imersão, foi aprofundado ainda mais a utilização do ChatGPT como uma ferramenta auxiliar no Google Sheets e, foi explorado a criação de gráficos, uma habilidade fundamental na visualização de dados. Um destaque importante da aula foi a apresentação de uma nova ferramenta de IA projetada para auxiliar na manipulação e análise de dados, o [`Sheet+`](https://sheetplus.ai), permitindo que os participantes ampliem ainda mais suas capacidades na área de análise de dados, aproveitando o poder da inteligência artificial.
#### Desafios propostos
  - Personalizar o gráfico para adicionar as quantidades no gráfico
  - Analisar qual o gráfico ideal para os demais gráficos a serem adicionados, usando o guia citado pelo instrutor Marcell, CEO da PM3 
  - Realizar uma análise exploratória e aplicar as mesmas técnicas, incluindo a criação de gráficos, a uma nova base de dados do Kaggle: base de dados de hoteis chamada [`Hotels in Munnar, Kerala (MakeMyTrip)`](https://www.kaggle.com/datasets/andrewgeorgeissac/hotels-in-munnar-kerala).
##
### 🤿 Aula 3: Conectando bases de dados e usando a extensão do ChatGPT
#### Introdução
  Na terceira aula desta imersão, foi explorada uma nova base de dados, contendo dados de produtos, relacionada à "Amazon Sales Dataset". Durante a aula, foi demonstrado como conectar essa base à anterior, utilizando uma coluna comum a ambas. Além disso, uma extensão foi apresentada, o SheetGPT, que permite que o ChatGPT fosse incorporado ao Google Sheets, possibilitando a realização de traduções, resumos e análises de sentimento de críticas.
  A aula também se concentrou na transmissão dos principais conceitos de Engenharia de Prompt, incluindo o uso de "few-shot" com a cadeia de pensamento, com o objetivo de obter respostas mais precisas de IAs generativas, como o ChatGPT.
#### Sobre a nova base de dados "Dados"
  Informações representadas por cada coluna na nova planilha de dados:
  - product_id: ID do produto
  - user_id: ID único do usuário
  - user_name: Nome escolhido pelo usuário
  - review_id: ID da crítica
  - review_title: Título da crítica
  - review_content: Conteúdo da crítica
  - img_link: Link da imagem do produto
#### Desafio proposto
- Gerar a tradução das críticas e fazer uma análise de sentimentos das mesmas, usando a extensão SheetGPT, em uma nova base de dados do Kaggle: [`Threads, an Instagram app Reviews`](https://www.kaggle.com/datasets/saloni1712/threads-an-instagram-app-reviews), base de críticas do aplicativo Threads
##
### 🤿 Aula 4: Manipule planilhas com Phyton Pandas e o ChatGPT
#### Introdução 
  Nessa quarta aula, foi introduzido o Google Colab, serviço de nuvem gratuito hospedado pelo próprio Google para incentivar a pesquisa de Aprendizado de Máquina e Inteligência Artificial. É uma ferramenta que permite que você misture código fonte (geralmente em python) e texto rico (geralmente em markdown) com imagens e o resultado desse código, uma técnica conhecida como: notebook (“caderno”, em português).
  Foi realizado um mergulho em Python e na biblioteca de manipulação de dados Pandas, demonstrando como tabelas podem ser importadas e análises iniciais podem ser conduzidas com os comandos mais importantes. Tudo isso, sempre com o auxílio do ChatGPT.
#### Desafios propostos
- Usando o Google Colab com Python e Pandas, criar uma nova coluna chamada “actual_price_real”, que será o valor da coluna “actual_price”, originalmente em rúpias indianas, convertido para reais
- Realizar as análises que foram executadas nas aulas anteriores usando o Google Sheets, mas agora utilizando Python e Pandas no Google Colab
- Conectar as duas planilhas usadas nas aulas anteriores, como fizemos com o VLOOKUP, mas usando Python e Pandas
- Colocar a base já corrigida na biblioteca Pandas Profiling citada no conteúdo extra
##
<div align="center">
  
<img width="800" alt="gif_fundo_do_mar" scr="/images/gif_fundo_do_mar.gif">
  
</div>

##
### 💻 Resultados 

#### 👩‍💻 Aula 1: Análise exploratória da base de dados e chatGPT

*• Adicionar a formatação condicional de cores à coluna de porcentagens (no dataset "Amazon Sales Dataset")*
  <div> <br>
<div> 
  <div> 
    
  ![base_dados_amazon_dados](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/8e838385-7cbc-4403-955a-754ae8298ea8)
  </div> <br>
  
  Note que a coluna "percent", que corresponde à porcentagem de desconto sobre o preço do produto, está colorida, e os tons da cor verde variam de acordo com o valor da célula. Isso se dá por conta da formatação condicional na célula. Optei por fazer quatro regras, sendo elas:
  <div align="center">
    <br>
    <img width="260" alt="bd_amazon_formatacao_condicional" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/95b2b6f9-2931-4664-8e6e-2f6b00fbbd2c" target="_blank">
  </div> <br><br>
</div>
<div>
    
  *• Realizar uma análise exploratória e aplicar as mesmas técnicas utilizando o ChatGPT a uma nova base de dados do Kaggle: Top 1000 IMDb Movies Dataset*
  <div> <br>
    Seguindo as instruções da aula da imersão, foi explicado como escrever um prompt para que o ChatGPT dê as instruções de como realizar uma análise exploratória no Google Sheets. A dica é escrever o prompt fornecendo o máximo de informações possíveis sobre a base de dados, para que não haja outras interpretações, dessa forma, a resposta será mais concisa e alinhada com a dúvida.
  </div>
  <div align="center"> <br>
    <img width="400" alt="chatGPT_instrucoes1" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/226f5200-cfe5-4df7-a290-6c75e4f50d74" target="_blank">
  </div> <br>
      Logo após a importação e análise das colunas, procurei limpar os dados contidos nas colunas da maneira mais correta possível. Havia números em branco nas colunas "Metascore of Movie" e "Gross", estudei o que pode ser colocado em casos de dados vazios, e decidi colocar "No information" em todas as células vazias. Outro problema encontrado foi a formatação dos números da coluna "Gross" e foi trocado a formatação para número do tipo moeda. Além disso, depois da realizar a limpeza, optei por adicionar mais informação na base de dados, sendo elas: nome "Position" na coluna contendo as posições das classificações dos filmes, coluna "Movie Name Language", coluna "Genres", coluna "Main Genre", coluna "Second Genre" e coluna "Third Genre". Também, Para facilitar a visualização de alguns dados, adicionei formatação condicional às colunas "Movie Rating" e "Metascore of Movie".
  <div></div><br>
  
- Antes das modificações

  <div align="center"> <br>
    <img alt="bd_imdb_movies_sem_modificacoes" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/57ab6f74-ab6f-48e0-bdfa-ff50f5683ee5" target="_blank">
  </div> <br>
  
- Depois das modificações
  
  <div align="center"> <br>
    <img alt="bd_imdb_movies" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/d99b91e7-5ae2-4f23-a1eb-cc66629e8976" target="_blank">
  </div> <br><br>
Mais detalhes de cada modificação: <br><br>
- Coluna "Movie Name Language": <br>
  
  Fórmula foi feita com o comando "[`DETECT LANGUAGE`](https://support.google.com/docs/answer/3093278?hl=en)" e "[`MAIÚSCULA`](https://support.google.com/docs/answer/3094219?hl=pt-BR)". <br><br>
  <div align="center">
  <img width="450" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/755093c7-38a3-47e1-a68a-7528fd54dea8">
  </div> <br>

- Coluna "Genres" <br>
  Procurei outra base de dados que possuísse os gêneros dos filmes e acabei encontrando uma chamada [`"IMDB movies dataset"`](https://www.kaggle.com/datasets/ashpalsingh1525/imdb-movies-dataset) que continha a maioria dos filmes da base de dados original, fiz um "[`VLOOKUP`](https://support.google.com/docs/answer/3093318?hl=en)" (mais conhecido como PROCV), em conjunto com o "[`SEEROO`](https://support.google.com/docs/answer/3093304?hl=pt-BR)", para adicionar os gêneros existentes da nova base de dados para a antiga, e os que ficaram com o valor zero, acabei colocando manualmente mesmo. <br><br>
  <div align="center">
  <img width="500" alt="coluna_genero_filme" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/e0f90643-f244-4631-99ca-b543bada1cf1"> <br>
  </div><br>

    - Coluna "Main Genre" <br><br>

      Fórmula foi feita com a função "[`SPLIT`](https://support.google.com/docs/answer/3094136?hl=pt-BR)", para separar o primeiro gênero que é listado na string localizada na coluna "Genres", juntamente com o "[`ARRUMAR`](https://support.google.com/docs/answer/3094140?hl=pt-BR&sjid=6982433507484744947-SA)", para retirar os espaços a mais na string, e também, com o "[`SEEROO`](https://support.google.com/docs/answer/3093304?hl=pt-BR)". <br>
    <div align="center"> <br>
    <img width="450" alt="coluna_genero_principal" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/32a96e74-75a8-4602-89e6-acd04078503e">
    </div>
    <br> 
    
    - Coluna "Second Genre" <br>

    <div align="center"> <br>
    <img width="450" alt="coluna_segundo_genero" scr="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/ed187a3e-fb85-4d63-88c4-d665d2eecc82">
    </div>
    <br>
  
    - Coluna "Third Genre" <br>
    
    <br>

  
  <div>
Informações da base de dados:
    
- Position: posição da classificação do filme (de 1 a 1000)
- Movie Name: Nome do filme
- Movie Name Language: Idioma do nome do filme
- Watch Time: Duração do filme, em minutos
- Genres: Gêneros dos filmes
- Main Genre: Gênero principal do filme
- Second Genre: Segundo gênero mais predominante do filme
- Third Genre: Terceiro gênero mais predominante do filme
- Movie Rating: Nota do filme de zero (0) à dez (10)
- Metascore of Movie: É uma pontuação atribuída por críticos de cinema para avaliar a qualidade e o mérito de um filme. Essa pontuação vai de zero (0) à cem (100)
- Gross: Representa as arrecadações brutas, em dinheiro, que um filme ganhou em bilheteria em todo o mundo
- Votes: Quantidade de votos recebidos por usuários do IMDb
- Director: Diretor do filme (será preenchido em breve, e gráficos com essas informações serão desenvolvidos)
- Description: Descrição/Sinopse do filme 


  <br> <div align="center">
    <img width="400" alt="chatGPT_instrucoes2" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/4f18a7f7-18ab-4d22-9196-ea2ca7e3eead" target="_blank">
  </div>
  <div align="center">
    <img width="400" alt="chatGPT_instrucoes3" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/d31e37f3-9eb4-4c8f-9a2d-ca06a6603062">
  </div>
  
</div>
</div> <br>

#### 👩‍💻 Aula 2: Manipule planilhas e crie gráficos com ajuda da IA
<div>
  
*• Personalizar o gráfico para adicionar as quantidades no gráfico*
</div>
*• Analisar qual o gráfico ideal para os demais gráficos a serem adicionados, usando o guia citado pelo instrutor Marcell, CEO da PM3*
*• Realizar uma análise exploratória e aplicar as mesmas técnicas, incluindo a criação de gráficos, a uma nova base de dados do Kaggle: base de dados de hoteis chamada Hotels in Munnar, Kerala (MakeMyTrip)*

#### 👩‍💻 Aula 3: Conectando bases de dados e usando a extensão do ChatGPT
*• Gerar a tradução das críticas e fazer uma análise de sentimentos das mesmas, usando a extensão SheetGPT, em uma nova base de dados do Kaggle: Threads, an Instagram app Reviews*

#### 👩‍💻 Aula 4: Manipule planilhas com Phyton Pandas e o ChatGPT
*• Usando o Google Colab com Python e Pandas, criar uma nova coluna chamada “actual_price_real”, que será o valor da coluna “actual_price”, originalmente em rúpias indianas, convertido para reais*
*• Realizar as análises que foram executadas nas aulas anteriores usando o Google Sheets, mas agora utilizando Python e Pandas no Google Colab*
*• Conectar as duas planilhas usadas nas aulas anteriores, como fizemos com o VLOOKUP, mas usando Python e Pandas*
*• Colocar a base já corrigida na biblioteca Pandas Profiling citada no conteúdo extra*


 
##
### 🗃️ Organização do repositório
#### Overview

#### Pasta "bd_amazon_products_imersao"
![base_dados_amazon_dados](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/8e838385-7cbc-4403-955a-754ae8298ea8)
![base_dados_amazon_avaliacoes](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/5891cdf8-330a-4a76-a651-2fb170ef066a)
![image](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/7be95a73-9c3d-4951-8cee-676eafe01529)
![image](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/ae929b90-1c16-4e2b-b556-7c46417c58d2)
![image](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/c1faf2ff-c235-453b-96ed-e8a169804daf)
![image](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/68000ef5-8a25-4d6f-a880-a0872f1264c3)
![image](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/7523f316-7023-401f-b059-1fcbc29fc266)
![image](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/9cdf9740-761e-4fd8-a14b-39258b7747fd)
![image](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/5c7af85f-8eda-4320-b0ef-36f028e56f4f)
![image](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/20d808de-f7e5-44de-945e-49c2bda1a98a)

#### Pasta "bd_top1000_IMDb_movies"

#### Pasta "bd_hotels_munnar"

#### Pasta "bd_threads_review"

#### Pasta "images"
Pasta contendo recursos visuais utilizadas no README 

##
### 📑 Melhorias futuras para o projeto
#### bd_amazon_products_imersao
- Criar tabelas dinâmicas
- Colocar diferentes tipos de gráficos

#### bd_top1000_IMDb_movies
- Adicionar a coluna "Director"
- Adicionar nuvem de palavras com os gêneros que aparecem na base de dados
- Incluir e desenvolver um elemento visual para mostrar quais são os diretores que mais apareceram na base de dados, evidenciando quem fez os filmes mais bem avaliados
- Criar tabelas dinâmicas

#### bd_hotels_munnar

#### bd_threads_review

##
### 🔗 Hashtags
#alura #alura_dados_ia #7DaysOfCode

<img width=100% alt="blue_waves_end" src="https://capsule-render.vercel.app/api?type=waving&color=2132a6&height=120&section=footer"/>

