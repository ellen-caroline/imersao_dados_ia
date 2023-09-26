<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=2132a6&height=120&section=header"/>

<h3 align="center"> Imersão Dados: Análises com Inteligência Artificial - Alura </h3>

##
<div align="center">
  <img align="center" width="70" alt="chatGPT-badge" src="https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white" target="_blank">
  <img align="center" width="70" alt="kaggle-badge" src="https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white" target="_blank">
</div>
<div>
  <p align="center">
    <img align="center" width="250" src="/images/diver.png">
  </p>
</div>

##
### 📁 Descrição do projeto
Esse projeto foi desenvolvido durante a [`Imersão Dados_IA`](https://www.alura.com.br/imersao-dados-ia), disponibilizada pela [`Alura`](https://www.alura.com.br/), com o objetivo de introduzir a habilidade e técnicas de análise de dados a pessoas interessadas por tecnologia, afim de desenvolver e aprimorar habilidades em Excel, Python e ferramentas de IA. Dentre algumas tecnologias apresentadas pelos instrutores, estão: ChatGPT, Google Sheets, Google Colab e Bing.AI. Foi uma imersão que pontuou sobre o impacto significativo que as inteligências artificiais estão causando no mundo e as diversas maneiras de aplicá-las.
##
### 🤿 Aula 1: Análise exploratória da base de dados e chatGPT
#### Introdução 
  A primeira aula do curso apresenta o Kaggle como plataforma e utiliza uma base de dados de compras da Amazon para realizar uma análise exploratória. Além disso, o ChatGPT é introduzido como uma ferramenta auxiliar na geração de fórmulas básicas no Google Sheets. Foi disponibilizado uma base de dados [`"Amazon Sales Dataset"`](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset) (traduzido para o português, Vendas da Amazon Dataset), do Kaggle, com o intuito de acompanhar e realizar as atividades propostas durante a aula.
#### Sobre a base de dados "Avaliações"
  Na planilha de dados da Amazon, havia as seguintes informações: 
  - product_id: ID do produto
  - product_name: Nome do produto
  - category: Categoria do produto
  - actual_price: Valor do produto com desconto
  - product_price: Valor do produto com valor cheio
  - rating: Valor de 0 a 5 avaliando o produto
  - rating_count: Quantidade de pessoas que avaliaram o produto
  - about_product: Descrição do produto
  - product_link: Link do produto na loja da Amazon

#### Desafios propostos
  -	Adicionar a formatação condicional de cores à coluna de porcentagens (no dataset "Amazon Sales Dataset")
  -	Realizar uma análise exploratória e aplicar as mesmas técnicas utilizando o ChatGPT a uma nova base de dados do Kaggle: [`Top 1000 IMDb Movies Dataset`](https://www.kaggle.com/datasets/inductiveanks/top-1000-imdb-movies-dataset) 
##
### 🤿 Aula 2: Manipule planilhas e crie gráficos com ajuda da IA
#### Introdução
  Na segunda aula do curso, foi aprofundado ainda mais a utilização do ChatGPT como uma ferramenta auxiliar no Google Sheets e, foi explorado a criação de gráficos, uma habilidade fundamental na visualização de dados. Um destaque importante da aula foi a apresentação de uma nova ferramenta de IA projetada para auxiliar na manipulação e análise de dados, o [`Sheet+`](https://sheetplus.ai), permitindo que os participantes ampliem ainda mais suas capacidades na área de análise de dados, aproveitando o poder da inteligência artificial.
#### Desafios propostos
  - Personalizar o gráfico para adicionar as quantidades
  - Analisar qual o gráfico ideal para o seu caso usando o guia citado pelo Marcell, que está nos links da aula
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
- Gerar a tradução das críticas e fazer uma análise de sentimentos das mesmas, usando a extensão SheetGPT, em uma nova base de dados do Kaggle: [`Threads, an Instagram app Reviews`](https://www.kaggle.com/datasets/saloni1712/threads-an-instagram-app-reviews), base de críticas do aplicativo Threads.
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
### Resultados
#### Aula 1
##

##### Hashtags
#alura #alura_dados_ia #7DaysOfCode




<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=2132a6&height=120&section=footer"/>

