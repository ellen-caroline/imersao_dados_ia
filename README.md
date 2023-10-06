<img width=100% alt="blue_waves_head" src="https://capsule-render.vercel.app/api?type=waving&color=2132a6&height=120&section=header"/>

<h3 align="center"> Imersão Dados: Análises com Inteligência Artificial - Alura </h3>

##
<div align="center">
  <img align="center" width="70" alt="chatGPT-badge" src="https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white" target="_blank">
  <img align="center" width="70" alt="kaggle-badge" src="https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white" target="_blank"><br>
</div>
<div style="padding: 150">
  <p align="center">
    <img align="center" width="250" alt="um mergulhador, tons escuros cinzentos e há um pequeno detalhe vermelho na roupa, e o fundo é transparente (png). Estilo: arte digital." target="_blank" src="/images/diver.png">
  </p>
</div>

##
  
### 📁 Descrição do projeto

   Esse projeto foi desenvolvido durante a [`Imersão Dados_IA`](https://www.alura.com.br/imersao-dados-ia), disponibilizada pela [`Alura`](https://www.alura.com.br/), com o objetivo de introduzir a habilidade e técnicas de análise de dados a pessoas interessadas por tecnologia, afim de desenvolver e aprimorar habilidades em Excel, Python e ferramentas de IA. Dentre algumas tecnologias apresentadas pelos instrutores, estão: ChatGPT, Google Sheets, Google Colab e Bing.AI. Foi uma imersão que pontuou sobre o impacto significativo que as inteligências artificiais estão causando no mundo e as diversas maneiras de aplicá-las.
##
### 🤿 Aula 1: Análise exploratória da base de dados e chatGPT
#### Introdução 
  A primeira aula da imersão apresenta o Kaggle como plataforma e utiliza uma base de dados de compras da Amazon para realizar uma análise exploratória. Além disso, o ChatGPT é introduzido como uma ferramenta auxiliar na geração de fórmulas básicas no Google Sheets. Foi disponibilizado uma base de dados "[`Amazon Sales Dataset`](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)" (traduzido para o português, Vendas da Amazon Dataset), do Kaggle, com o intuito de acompanhar e realizar as atividades propostas durante a aula. 
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
  
<img width="800" alt="Gif do fundo do mar com uma pessoa de cabelo comprido no centro para baixo. Possui um ecossistema com grande biodiversidade, há baleias . As baleias são da cor azul claro e estão nadando, bem ao fundo da imagem, direção de baixo para cima, e há peixes das cores azul claro, amarelo, laranja, branco e brilhante, nadando em diversas direções. Também há um recife de corais nas cores azul e verde e há plantas aquáticas. Estilo: arte digital." src="/images/gif_fundo_do_mar.gif">
  
</div>

##
### 💻 Resultados 

#### 👩‍💻 Aula 1: Análise exploratória da base de dados e chatGPT

*• Adicionar a formatação condicional de cores à coluna de porcentagens (no dataset "Amazon Sales Dataset")*
  <div> <br>
<div> 
  <div> 
    
  ![Visão geral do bando de dados "Amazon Sales Dataset". Possui as seguintes colunas: id_product (id do produto), product_name (nome do produto), category (categorias), category_geral (categoria principal oi geral), subcategory (subcategoria), actual_price (preço do produto atual, em rúpias indianas), product_price(preço do produto sem desconto), percent (porcentagem do desconto do produto), actual_price_real (preço atual do produto, em reais), rating (nota da avaliação do produto, valores vão de 0 a 5), rating_count (quantidade de avaliações do produto), about_product (informações do produto), product_link (link do produto), review_title (título da avaliação) e review_content (contpudo da avaliação). As colunas percent e rating estão coloridas em verde.](https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/8e838385-7cbc-4403-955a-754ae8298ea8)
  </div> <br>
  
  Note que a coluna "percent", que corresponde à porcentagem de desconto sobre o preço do produto, está colorida, e os tons da cor verde variam de acordo com o valor da célula. Isso se dá por conta da formatação condicional na célula. Optei por fazer quatro regras, sendo elas:
  <div align="center">
    <br>
    <img width="260" alt="Formatação condicional. Nela, há quatro condições: a primeira é da cor rosa pálido e sua condição é 'Valor é igual ou maior que 99%', a segunda é verde escuro dessaturado e sua condição é 'Valor é igual ou maior que 75%', a terceira é um verde mais claro que o anterior e sua condição é 'Valor é igual ou maior que 50%', e a quarta e última é um verde ainda mais claro que o anterior e sua condição é 'Valor é igual ou maior que 25%'. Dessa forma, números menores que 25% ficam com a célula branca." src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/95b2b6f9-2931-4664-8e6e-2f6b00fbbd2c" target="_blank">
  </div> <br><br>
</div>
<div>
    
  *• Realizar uma análise exploratória e aplicar as mesmas técnicas utilizando o ChatGPT a uma nova base de dados do Kaggle: Top 1000 IMDb Movies Dataset*
  <div>
    Seguindo as instruções da aula da imersão, foi explicado como escrever um prompt para que o ChatGPT dê as instruções de como realizar uma análise exploratória no Google Sheets. A dica é escrever o prompt fornecendo o máximo de informações possíveis sobre a base de dados, para que não haja outras interpretações, dessa forma, a resposta será mais concisa e alinhada com a dúvida.
  </div>
  <div align="center"> <br>
    <img width="400" alt="Parte de uma conversa com o chatGPT. O ChatGPT instrui a fazer a análise de dados seguindo passos, e na imagem contém os seguintes passos: Passo 1: Importação dos Dados: 1.1 Abra uma nova planilha no Google Sheets. 1.2 Clique em 'Arquivo' e escolha 'Importar' ou 'Fazer upload' para carregar o arquivo de dados (que provavelmente está em formato CSV ou Excel). 1.3 Certifique-se de que os dados são importados corretamente nas colunas apropriadas. Passo 2: Análise das Colunas: 2.1 Revise as colunas disponíveis na sua planilha para entender o que cada uma representa. Você já descreveu o significado das colunas, mas essa etapa é importante para uma análise mais aprofundada. Passo 3: Limpeza de Dados (se necessário): 3.1 Verifique se há valores ausentes em alguma coluna e decida como lidar com eles (remover linhas, preencher valores, etc.). 3.2 Certifique-se de que os tipos de dados em cada coluna estejam corretos (por exemplo, as colunas de ano devem ser do tipo numérico, não texto)." src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/226f5200-cfe5-4df7-a290-6c75e4f50d74" target="_blank">
  </div> <br>
  <div>
    Após importar e analisar as colunas, foram realizadas várias etapas de limpeza e aprimoramento dos dados. Primeiramente, foram identificados números em branco nas colunas "Metascore of Movie" e "Gross". Para lidar com esses dados ausentes, foi tomada a decisão de preencher todas as células vazias com o valor "No information". Isso garante que os campos vazios sejam devidamente identificados. 
  Além disso, a formatação dos números na coluna "Gross" foi ajustada para o formato de moeda, o que facilita a leitura e interpretação dos valores financeiros. 
<br><br>  
Para enriquecer ainda mais a base de dados, foram adicionadas várias novas informações. Estas incluem: 
<br><br>
    
- Nomear a primeira coluna, que contém as posições das classificações dos filmes, de "Position".
- Uma nova coluna chamada "Movie Name Language" para especificar o idioma do nome do filme.
- Colunas separadas para "Genres" (Gêneros), "Main Genre" (Gênero Principal), "Second Genre" (Segundo Gênero) e "Third Genre" (Terceiro Gênero) para categorizar os filmes com mais detalhes quanto aos gêneros a que pertencem.  
<br>
  Também, foram aplicadas formatações condicionais às colunas "Movie Rating" (Avaliação do Filme) e "Metascore of Movie" (Metascore do Filme) para melhorar a visualização dos dados. Essas formatações condicionais ajudam a destacar informações importantes ou valores fora do padrão, tornando mais fácil a identificação de tendências e insights na base de dados.
<br><br>
  Essas modificações e melhorias foram realizadas com o objetivo de tornar a base de dados mais completa, informativa e fácil de usar para análises subsequentes.
</div><br>
  
- Antes das modificações

  <div align="center"> <br>
    <img alt="Banco de dados 'Top 1000 IMDb Movies' antes de ser modificado" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/57ab6f74-ab6f-48e0-bdfa-ff50f5683ee5" target="_blank">
  </div> <br>
  
- Depois das modificações
  
  <div align="center"> <br>
    <img alt="Banco de dados 'Top 1000 IMDb Movies' depois de modificado, com colunas e informações adicionadas, que serão explicadas mais detalhadamente abaixo." src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/d99b91e7-5ae2-4f23-a1eb-cc66629e8976" target="_blank">
  </div> <br>
Mais detalhes de cada modificação: <br><br>
- Coluna "Movie Name Language" <br>
  
  A fórmula foi criada utilizando os comandos "[`DETECT LANGUAGE`](https://support.google.com/docs/answer/3093278?hl=en)" para detecção de idioma e "[`MAIÚSCULA`](https://support.google.com/docs/answer/3094219?hl=pt-BR)" para converter o texto em letras maiúsculas. <br>
  <br><br>
  <div align="center">
  <img width="450" alt="Coluna 'Movie Name Language', mostra a seguinte fórmula nas células: =MAIÚSCULA(DETECTLANGUAGE(B2))." src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/755093c7-38a3-47e1-a68a-7528fd54dea8">
  </div> <br>

- Coluna "Genres" <br><br>
  Foi feita utilizando outra base de dados que possuísse os gêneros dos filmes e acabei encontrando uma chamada "[`IMDB movies dataset`](https://www.kaggle.com/datasets/ashpalsingh1525/imdb-movies-dataset)" que continha a maioria dos filmes da base de dados original. Na fórmula, para extrair os gêneros dos filmes que tinha na base de dados original, utilizei "[`VLOOKUP`](https://support.google.com/docs/answer/3093318?hl=en)" (mais conhecido como PROCV), em conjunto com o "[`SEEROO`](https://support.google.com/docs/answer/3093304?hl=pt-BR)", com o objetivo de adicionar os gêneros existentes da nova base de dados para a antiga. E os que ficaram com o valor zero, acabei colocando manualmente mesmo.    <br>
  <br>
    <div align="center">
    <img width="650" alt="Coluna 'Genres', mostra a seguinte fórmula: =SEERRO(SE(PROCV(B2;$A$2:$A$1001;1;FALSO) = B2; PROCV(A2;$B$2:$C$1001;2;FALSO); 0);0)." src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/e0f90643-f244-4631-99ca-b543bada1cf1"> <br>
    </div><br>

     - Coluna "Main Genre" <br><br>
     Fórmula foi feita com a função "[`SPLIT`](https://support.google.com/docs/answer/3094136?hl=pt-BR)", para separar o primeiro gênero que é listado na string localizada na coluna "Genres", juntamente com o "[`ARRUMAR`](https://support.google.com/docs/answer/3094140?hl=pt-BR&sjid=6982433507484744947-SA)", para retirar os espaços a mais na string, e também, com o "[`SEEROO`](https://support.google.com/docs/answer/3093304?hl=pt-BR)".
      <br><br>
    <div align="center"> <br>
    <img width="650" alt="Coluna 'Main Genre', mostra a seguinte fórmula nas células: =SEERRO(ARRUMAR(SPLIT(F2; ',')); ''). Observação: As aspas simples na realidade são aspas duplas." src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/32a96e74-75a8-4602-89e6-acd04078503e">
      
    </div>
    <br> 
    
    - Coluna "Second Genre" <br><br>
     A fórmula utiliza as funções "[`EXT.TEXTO`](https://support.microsoft.com/pt-br/office/ext-texto-ext-textob-funções-ext-texto-ext-textob-d5f9e25c-d7d6-472e-b568-4ecb12433028)", que pega parte do texto em F após a posição indicada em G, "[`REGEXEXTRACT`](https://support.google.com/docs/answer/3098244?hl=en)", usada para extrair um padrão de texto que corresponda ao regex "([^,]+)", que significa qualquer sequência de caracteres que não contenha vírgulas, "[`ARRUMAR`](https://support.google.com/docs/answer/3094140?hl=pt-BR&sjid=6982433507484744947-SA)" e "[`SEERRO`](https://support.google.com/docs/answer/3093304?hl=pt-BR)" para extrair o segundo gênero da coluna "Genres", enquanto remove espaços em branco e caracteres não imprimíveis. Se ocorrer algum erro, a fórmula retorna uma string vazia como resultado.
    <br><br>
    <div align="center"> <br>
    <img width="650" alt="coluna_segundo_genero" src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/efcb6d97-1561-42d3-8f20-1896be39da4b">

    </div>
    <br>
  
    - Coluna "Third Genre" <br><br>
    Essa fórmula extrai o terceiro gênero da coluna 'Genres' (coluna F) e o coloca na coluna I. Se não houver terceiro gênero, a célula na coluna I ficará em branco (string vazia). A função "[`EXT.TEXTO`](https://support.google.com/docs/answer/3094129?hl=pt-BR)MID(F2, LEN(G2) + LEN(H2) + 3, LEN(F2))" isola a parte da célula 'Genres' que contém o terceiro gênero, começando após os dois primeiros gêneros e as vírgulas. A "[`REGEXEXTRACT`](https://support.google.com/docs/answer/3098244?hl=pt-BR&sjid=7725968779022548553-SA)" foi utilizada para encontrar um trecho de texto que corresponda ao padrão de expressão regular "([^,]+)", que significa "um ou mais caracteres que não são vírgulas". Isso captura o terceiro gênero da string extraída. E, sempre em conjunto, a função "[`SEERRO`](https://support.google.com/docs/answer/3093304?hl=pt-BR)" e "[`ARRUMAR`](https://support.google.com/docs/answer/3094140?hl=pt-BR&sjid=6982433507484744947-SA)".

    <br>
    <div align="center"> <br>
    <img width="650" alt="Coluna terceiro gênero, mostra a função SEERRO(ARRUMAR(REGEXEXTRACT(EXT.TEXTO(F2; NÚM.CARACT(G2)+NÚM.CARACT(H2)+3; NÚM.CARACT(F2)); '([^,]+)')); ''). Observação: As aspas simples na realidade são aspas duplas." src="https://github.com/ellen-caroline/imersao_dados_ia/assets/106993186/a6c008b8-197d-4c9e-9b5e-682413e8212e">

   </div>
  <br>
  
  <div>
De maneira geral e resumida, essas são as informações da base de dados:
    
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
  
- *Personalizar o gráfico para adicionar as quantidades no gráfico*
  
</div>

- *Analisar qual o gráfico ideal para os demais gráficos a serem adicionados, usando o guia citado pelo instrutor Marcell, CEO da PM3*
- *Realizar uma análise exploratória e aplicar as mesmas técnicas, incluindo a criação de gráficos, a uma nova base de dados do Kaggle: base de dados de hoteis chamada Hotels in Munnar, Kerala (MakeMyTrip)*

#### 👩‍💻 Aula 3: Conectando bases de dados e usando a extensão do ChatGPT

- *Gerar a tradução das críticas e fazer uma análise de sentimentos das mesmas, usando a extensão SheetGPT, em uma nova base de dados do Kaggle: Threads, an Instagram app Reviews*

#### 👩‍💻 Aula 4: Manipule planilhas com Phyton Pandas e o ChatGPT

- *Usando o Google Colab com Python e Pandas, criar uma nova coluna chamada “actual_price_real”, que será o valor da coluna “actual_price”, originalmente em rúpias indianas, convertido para reais*
- *Realizar as análises que foram executadas nas aulas anteriores usando o Google Sheets, mas agora utilizando Python e Pandas no Google Colab*
- *Conectar as duas planilhas usadas nas aulas anteriores, como fizemos com o VLOOKUP, mas usando Python e Pandas*
- *Colocar a base já corrigida na biblioteca Pandas Profiling citada no conteúdo extra*

##
### 🗃️ Organização do repositório
#### Overview

#### Pasta "bd_amazon"
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

#### Pasta contendo recursos visuais utilizadas no README 

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

<div align="center">
<img width="100" alt="Gif de um carangueijo laranja andando com fundo transparente" src="https://i.imgur.com/uTkEUww.gif">
</div>

##
### 🔗 Hashtags
#alura #alura_dados_ia #7DaysOfCode

##

### 📚 Referências
- [Cartilha: O uso correto do texto alternativo](https://www.gov.br/governodigital/pt-br/acessibilidade-digital/uso-correto-texto-alternativo.pdf)
- Mídias: 
  - Gif do fundo do mar: [`Mienar`](https://mienar.tumblr.com/post/184976994089/commission-for-kelseylorene-instagram-shop)
  - Gif caranqueijo: [`Oleksiis`](https://imgur.com/gallery/J39Ds)

<img width=100% alt="blue_waves_end" src="https://capsule-render.vercel.app/api?type=waving&color=2132a6&height=120&section=footer"/>

