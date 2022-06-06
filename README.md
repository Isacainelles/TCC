#  APLICAÇÃO DA METODOLOGIA KDD E ALGORITMOS DE AGRUPAMENTO PARA ANÁLISE DE DADOS PROFISSIONAIS DA ÁREA DE TI
<p>Giovanna Santos da Silva</p>
<p>Isabella dos Santos Cainelles</p>

## Resumo
<p>O termo data mining (mineração de dados) é um processo de encontrar anomalias,
padrões e correlações em conjuntos de dados para prever resultados, sendo eles dados
complexos ou não, os dados complexos possuem mais potencial para obtenção de
resultados futuros. Esse trabalho tem como objetivo principal aplicar as técnicas do KDD
(Knowledge Discovery in Databases), e o algoritmo de agrupamento K-means para
encontrar padrões e correlações em uma base de dados de profissionais na TI.</p>
<p><b>Palavras-chave:</b> Mineração, Método KDD, Profissionais TI, Vagas, Cluster, K-means.</p>

## 1 Introdução
### 1.1 Contextualização
<p>De acordo com o IBGE (Instituto Brasileiro de Geografia e Estatística) existem cerca de
14,4 milhões de pessoas desempregadas no 2º semestre de 2021, isso considerando
pessoas que estão aptas a trabalhar (acima de 14 anos) e não estão trabalhando (IBGE,
2021).</p>
<p>Existem diversas causas para o desemprego, uma das principais é a baixa qualificação,
onde os entrevistados acabam perdendo oportunidade de trabalho por falta de
especialização (OLIVEIRA, 2014).</p>
<p>Além de saber onde procurar emprego, é importante saber a situação em que o mercado
de trabalho se encontra. As condições econômicas desfavoráveis podem reduzir a oferta
de emprego, e devido à redução na renda familiar, favorecem aos profissionais aceitarem
um emprego com baixa rentabilidade, um exemplo disso é a crise econômica agravada
pela pandemia do Covid19, por isso é importante investir em uma área que não cairá em
desuso no mercado de trabalho (REIS, 2019).</p>
<p>Para saber como está a situação do mercado de trabalho, é preciso fazer uma análise de
diversos dados relacionados para assim manter a veracidade e precisão dos dados.
Quando se observa a grande quantidade de dados inutilizados e deseja extrair
informações utiliza-se de uma técnica chamada mineração de dados que teve início nos
anos 80 e consiste em diversas técnicas de tratamento que buscam encontrar padrões e
relações entre os dados (AMO, 2006).</p>
<p>Dados isolados não possuem importância, o que torna a mineração de dados significativa
são as informações levantadas após a tratativa, assim são transformados em
conhecimento, o que facilita e auxilia a tomada de decisão, para apoiar na gestão do</p>
conhecimento existem ferramentas de Business Intelligence próprias para isso como por
exemplo o Power BI (PINHEIROS, 2020).</p>
<p>Para extrair informações relevantes por meio da análise minuciosa de grandes conjuntos
de dados, utiliza-se de padrões e técnicas estatísticas. Deste modo há métodos utilizados
para procura de conhecimento a partir de bases de dados, um deles por exemplo é
chamado de Knowledge Discovery in Databases (KDD ou Descoberta de Conhecimento
nas Bases de Dados) (QUONIAM, 2002).</p>
<p>O KDD é um procedimento para auxiliar na realização da tratativa, alguns pesquisadores
consideram-no como sinônimo de mineração de Data Mining (Mineração de Dados),
entretanto, outros consideram mineração de dados como uma etapa do KDD que consiste
5 fases (OLIVEIRA e SILVA, 2009).</p>
<p>A mineração de dados teve início nos anos 80, quando profissionais viram o grande
número de dados inutilizados dentro de uma empresa e com isso decidiram analisá-los. A
mineração de dados consiste em encontrar padrões e relações entre os dados para
prever resultados.</p>

### 1.2 Tema de Pesquisa
<p>A mineração de dados consiste na extração de informações e a utilização de uma
metodologia auxilia na assertividade na aplicação do data mining.
Este trabalho consiste em aplicar técnicas de mineração e algoritmos de agrupamentos
para encontrar padrões e relações na base de dados de profissionais da área de TI, para
isso será utilizado a metodologia KDD e o algoritmo de agrupamento K-means.</p>

### 1.3 Motivações e Justificativas
<p>É evidente que a baixa qualificação profissional é um dos motivos que mais impactam
para o desemprego. No ano de 2020, pode-se observar que as taxas de desemprego de
profissionais qualificados com 25 anos ou mais e ensino superior completo são inferiores
às de profissionais da mesma faixa etária que não possuem ensino superior, sendo,
respectivamente 7,5% e 14,7% (HALF, 2021).</p>
<p>Existem áreas dentro do setor de Tecnologia que estão com escassez de profissionais
qualificados, por isso é importante ter uma visão da situação do mercado de trabalho
(Assis, 2016).</p>
<p>O intuito deste trabalho é aplicar a metodologia KDD, as técnicas de mineração de dados
e alguns outros métodos como clustering para encontrar padrões e relações no âmbito do
profissional de TI. Assim, espera-se que o resultado dessa análise possibilite a obtenção
de informações sobre empregabilidade e os profissionais de TI.</p>

### 1.4 Objetivos
<p>O objetivo deste trabalho consiste na aplicação da metodologia KDD utilizando o algoritmo
k-means para identificar padrões sobre a empregabilidade de alunos de uma universidade
particular da área de TI. <p>
<p>Objetivos específicos:<p>
  
* Realizar pesquisa através de formulários para obtenção de dados
* Estudar sobre a metodologia KDD
* Preparação do ambiente para tratamento dos dados
* Realizar Levantamento de Requisitos
* Identificar a Base de Dados
* Realizar o pré-processamento dos Dados
* Aplicar os passos da metodologia KDD
* Realizar o processo de mineração de dados, usando técnicas de agrupamento
* Projetar as informações obtidas de forma visual.

## 2 Revisão Bibliográfica
<p>Nesta seção serão abordados os conceitos e trabalhos relacionados ao tema de
pesquisa.</p>

### 2.1 Conceitos Relacionados
<p>Nesta seção serão apresentados os seguintes conceitos relacionados: Banco de dados,
Desemprego, KDD, Data Mining, K-means.</p>

#### 2.1.1 Banco de Dados
<p>Banco de dados é o nome da estrutura criada para guardar dados “persistentes”, ou seja,
dados que não serão perdidos após o término de algum processo dentro do programa.
São considerados persistentes, pois uma vez gravados no banco de dados através dos
SGBDs, eles só poderão sofrer manipulações por meio de comandos também próprios
dos SGBDs (DATE, 2004).</p>

#### 2.1.2 Desemprego
<p>O desemprego, de forma simplificada, se refere às pessoas com idade para trabalhar
(acima de 14 anos) que não estão trabalhando, mas estão disponíveis e tentam encontrar
trabalho. Assim, para alguém ser considerado desempregado, não basta não possuir um
emprego. Veja alguns exemplos de pessoas que, embora não possuam um emprego, não
podem ser consideradas desempregadas:</p>

+ um universitário que dedica seu tempo somente aos estudos
+ uma dona de casa que não trabalha fora
+ uma empreendedora que possui seu próprio negócio
<p>De acordo com a metodologia usada pelo IBGE na Pesquisa Nacional por Amostra de
Domicílios Contínua – PNAD Contínua, o estudante e a dona de casa são pessoas que
estão fora da força de trabalho; já a empreendedora é considerada ocupada. (IBGE,
2021).</p>

#### 2.1.3 Linguagens Utilizadas
##### 2.1.3.1 Python
<p>A linguagem Python é possui uma sintaxe simples e objetiva, isso permite que seja usada
para administrar sistemas e desenvolver grandes projetos, ela está disponível
gratuitamente além de permitir o uso orientada a objetos é do tipo interpretada. É comum
observar a utilização do Python em diversas aplicações, por exemplo em arquitetura de
computadores ou sistema operacional, como Linux, Windows ou Mac OS e nas áreas de
inteligência artificial, banco de dados, aplicativos móveis (celulares), jogos e plataformas
web, como pode-se ver é muito versátil (PYTHON, 2022) (MENESES, 2010).</p>
<p>Em outras linguagens de programação encontram-se diversas marcações, como ponto (.)
ou ponto e vírgula (;), no fim de cada linha, no início e fim de bloco como chaves ({ }) ou
palavras. Esses marcadores agregam um certo nível de complexidade no código, já em
Python não temos essa preocupação. Python é uma linguagem completa, contando com
bibliotecas próprias para acessar bancos de dados, processar arquivos XML, construir
interfaces gráficas entre outras coisas, usando poucas linhas de códigos, isso torna o
programa mais rápido. Quando se utiliza bibliotecas próprias é possível se concentrar no
problema que deseja resolver, já que é desenvolvido e testado por outras pessoas
(PYTHON, 2022, MENESES, 2010).</p>

#### 2.1.4 KDD
<p>O KDD pode ser entendido como um processo da descoberta de novas correlações, é um
processo interativo que busca encontrar padrões e tendências relevantes, que sejam
válidos e grande potencial, por meio de uma análise crítica de grandes conjuntos de
dados. Este processo recorre às tecnologias de reconhecimento, que usam padrões e
técnicas matemáticas. O Data Mining ou a Mineração de Dados é uma das técnicas
utilizadas na realização do KDD (QUONIAM, 2002, GARCIA, 2008, FAYYAD,
PIATETSKY-SHAPIRO e SMITH, 1996).</p>
<p><b>Processos de KDD:</b></p>
<p><u>Seleção</u> - Etapa responsável por analisar os dados existentes em uma seleção, a serem
utilizados nas buscas de padrões e tendências (GARCIA, 2008) (FAYYAD,
PIATETSKY-SHAPIRO e SMITH, 1996).</p>
<p>Pré- Processamento - Tratamento dos dados obtidos na seleção para uso dos algoritmos.
Deve nessa fase retirar valores vazios ou inválidos da base analisada (GARCIA, 2008,
FAYYAD, PIATETSKY-SHAPIRO e SMITH, 1996).</p>
<p>Transformação - Etapa responsável por aplicar quando necessário transformações nos
dados, sejam elas lineares ou não lineares, geralmente é nessa etapa que são aplicadas
etapas de redução de dimensionalidade, que muitas vezes pode ser utilizada para análise
de cluster e projeção dos dados que nos permite prever certas informações relevantes
(GARCIA, 2008) (FAYYAD, PIATETSKY-SHAPIRO e SMITH, 1996).</p>
<p>Mineração - Responsável em encontrar padrões através da aplicação de algoritmos e
técnicas computacionais específicas (GARCIA, 2008, FAYYAD, PIATETSKY-SHAPIRO e
SMITH, 1996).</p>
<p>Interpretação - Responsável por analisar os resultados obtidos por todas as outras
etapas, mas especificamente, analisar os resultados da mineração dos dados, interpretar
e utilizar as informações obtidas para geração de conhecimento (GARCIA, 2008,
FAYYAD, PIATETSKY-SHAPIRO e SMYTH, 1996).</p>
<img src="[url](https://www.google.com/url?sa=i&url=http%3A%2F%2Fqnimate.com%2Funderstanding-html-img-tag%2F&psig=AOvVaw3iAzy6GeANwHvjYva2Jveb&ust=1654625316254000&source=images&cd=vfe&ved=0CAkQjRxqFwoTCOCoweW1mfgCFQAAAAAdAAAAABAD)"  width=60 height=40>
Figura 1 - Processo KDD

#### 2.1.5 Data Mining
<p>Conhecido como Data Mining todas as técnicas que nos permitem obter informações ou
conhecimentos e uma quantidade significativa de dados. O termo de mineração de dados
foi criado uma vez que se explora uma base de dados (mina) usando algoritmos
(ferramentas) adequados para obter conhecimento (minerais preciosos) (De CASTRO e
FERRARI, 2016).</p>
<p>As técnicas de mineração de dados são relevantes em todo o seu contexto, pois elas
podem ajudar na análise de big data de maneiras mais eficientes (OSMAN 2019).
Técnicas como essas envolvem etapas como coleta de dados, extração, análise e
métodos estatísticos. Existem muitas técnicas de mineração de dados: associação,
classificação, agrupamento, árvore de decisão, previsão, redes neurais etc. Cada uma
dessas técnicas tem regras específicas e tipos de problemas que elas resolvem (OSMAN
2019)</p>

##### 2.1.5.1 Agrupamento
<p>Clustering ou agrupamento é uma das primeiras técnicas usadas pela mineração de
dados. Esse processo envolve analisar uma ou mais características e encontrar
semelhanças entre os dados analisados, e assim entender a diferença entre esses dados.
Chamado também de segmentação pois esse método segmenta os dados em categorias
e assim os que tiverem características iguais a um determinado segmento se torna parte
daquele grupo, tendo assim vários agrupamentos, vários grupos ou conjuntos de dados
agrupados com suas semelhanças (OSMAN 2019).</p>

#### 2.1.6 K-Means
<p>K-Means é um algoritmo de agrupamento de mineração de dados um dos mais poderosos
e populares. Esse algoritmo utiliza uma partição de dados e definem uma regra para
agrupá-los O algoritmo inicia com os centroides, ou seja, os centros dos clusters e após
isso ele calcula as distâncias dos pontos e associa ao centro que aquele ponto estiver
mais perto (AHMED, SERAJ e ISLAM, 2020).</p>
Figura 2 - Exemplificação do K-means

### 2.2 Trabalhos Relacionados
<p>Pires, Ramos e Negretto (2021) desenvolveram uma aplicação da técnica de machine
learning na previsão de evasões em uma universidade particular, com o objetivo de
classificar estudantes em dois grupos: evadidos e não evadidos. Os autores utilizaram a
linguagem de programação Python para os algoritmos de classificação, enquanto a
linguagem R foi utilizada para o pré-processamento.</p>
<p>Neste trabalho, foram usados algoritmos de Árvore de decisão, KNN e SVM
implementados utilizando os recursos da biblioteca Scikit-Learn, e Rede Neural Artificial
onde foi utilizado o Tensorflow Keras. Para cada um desses algoritmos foi usado uma lista
de parâmetros customizados.</p>
<p>Como resultados, os autores obtiveram a comparação de melhor desempenho entre os
algoritmos de classificação, após uma bateria de testes realizados, através das análises
das medidas de desempenho: Acurácia, 1-Score, ROC e RMSE. A base de dados
utilizada foi disponibilizada pela universidade tendo apenas o curso de Sistemas de
Informação.</p>

## 3 Metodologia
<p>Nesta etapa do trabalho será apresentado o detalhamento da metodologia KDD e
informações das bases e algoritmos utilizados na fase de teste.</p>

### 3.1 Modelagem</p>

<p>Está sendo realizado uma pesquisa através de um formulário para coleta de dados dos
alunos do curso de Sistemas de Informação de uma Universidade Particular, dados como:
idade, sexo, cidade em que mora, graduação atual, área pretendida para se especializar,
trabalha atualmente, quanto tempo que trabalha, quantos empregos teve na área de TI,
quantas linguagem de programação domina, média de notas nas matérias (Gestão de
Projetos, Linguagem de Programação 3, Redes e Computadores 2, Banco de Dados 2),
possui cursos adicionais, quais são as áreas do cursos que realizou, estudou em escola
pública por quanto tempo?</p>
<p>Todos esses dados serão manipulados na ferramenta SQL Server, gerando assim a base
de dados sobre os profissionais atuais dessa universidade.</p>

### 3.2 Aplicação da Técnica KDD
#### 3.2.1 Seleção, Pré-Processamento e Transformação
<p>A técnica KDD é iniciada na fase de seleção onde serão selecionadas as tabelas que
serão relevantes para a análise. Após a seleção das tabelas o pré-processamento será
aplicado nas colunas relevantes e assim será feito um tratamento nos dados excluindo
dados nulos e gerando padrões de tipagens dos dados. A próxima fase é a fase de
mineração, na qual será aplicado o algoritmo K-means responsável por agrupar os dados.
A última fase aplicada será de interpretação, nessa etapa é feita uma avaliação das
informações obtidas para assim extraído conhecimento.</p>

#### 3.2.2 Mineração de dados e Interpretação
<p>A quarta fase do KDD é a mineração de dados e para a execução dela será utilizado o
algoritmo K-Means.</p>
<p>Para a aplicação do K-means é necessário importar a classe KMeans da biblioteca <b>sklearn.cluster</b> usando a linguagem Python.</p>
<b>form sklearn.cluster import KMeans</b>
<p>Será criado um objeto para que a classe K-Means seja iniciada e passando assim para
ela a quantidade de clusters que irá precisar, chamada atualmente de N.
A variável “kmeans” irá receber o retorno da função KMeans. Para a utilização da função,
é necessário passar dois parâmetros sendo o primeiro o número de clusters utilizados,
chamado de “N”, e o segundo uma função para geração de números aleatórios.</p>
<b>kmeans = KMeans (num_clusters=N, random_state )</b>
<p>A função “.fit()” será utilizada para o treinamento do Kmeans passando como parâmetro x
que representará as características da tabela.</p>
<b>kmeans.fit(x)</b>
<p>Na quinta e última fase será possível após a execução do algoritmo em todos os dados
disponibilizados, analisar os resultados obtidos através de gráficos que estão disponíveis
dentro do K-means.</p>

## 4 Resultados
<p>Após a aplicação da metodologia KDD e o algoritmo de agrupamento K-means espera-se
como resultado obter conhecimento através da tratativa dos dados que busca por padrões
e correlações entre as bases de profissionais.</p>
<p>A fim de testar o procedimento foi escolhida uma base de dados teste para aplicar as três
primeiras fases (Seleção, pré-processamento e transformação) da metodologia KDD.</p>
<p>A Tabela profissionais antes da aplicação das três primeiras etapas:</p>
Figura 3 -Tabela de resultado da pesquisa dos estudantes parte 1
Fonte: Imagem do autor
Figura 4 - Tabela de resultado da pesquisa dos estudantes parte 2
Fonte: Imagem do autor
Figura 5 -Tabela de resultado da pesquisa dos estudantes parte 3
Fonte: Imagem do autor
Figura 6 - Tabela de resultado da pesquisa dos estudantes parte 3
Fonte: Imagem do autor
<p>Tabela profissionais após a aplicação das três primeiras etapas.</p>
<p>Os dados foram padronizados, para isso foi feita a remoção de dados nulos, incorretos e
não utilizados. Os dados foram organizados em três tabelas diferentes, Informações
Pessoais e escolares, Empregabilidade e Informações Adicionais.</p>
<p>Primeira tabela, Informações pessoais e escolares:</p>
Figura 7 - Informações pessoais e escolares parte 1
Fonte: Imagem do autor
Figura 8 - Informações pessoais e escolares parte 2
Fonte: Imagem do autor
<p>Na coluna “Estudou qnt tempo em EP” a quantidade máxima que o aluno pode estudar do
ensino fundamental ao ensino médio em escola pública é de 12 anos, considerando a
antiga grade do ensino básico, segundo a Secretaria da Educação.</p>
<p>Segunda tabela, informações de empregabilidade:<p>
Figura 9 - Informações de empregabilidade parte 1
Fonte: Imagem do autor
<p>Para uma padronização dos dados da tabela foi utilizado o as regras a seguir:</p>
  
+ Nunca trabalhei sendo classificado como “0”
+ Menos de um ano sendo classificado como “1”
+ Entre 1 e 2 anos sendo classificado como “2”
+ entre 2 e 3 anos sendo classificado como “3”
+ Entre 3 e 4 anos sendo classificado como “4”
+ en Mais que 4 anos sendo classificado como “5”
<p>Terceira tabela, informações adicionais:</p>
Figura 10 - Informações adicionais parte 1
Fonte: Imagem do autor

## 5 Considerações Finais
<p>O objetivo principal é a aplicação do método KDD e a utilização do algoritmo K-Means
para encontrar relações entres os dados de profissionais de TI, os resultados da
mineração de dados só estarão disponíveis, após toda a finalização da aplicação do
método. Atualmente a pesquisa dos alunos ainda está acontecendo e irá ser
disponibilizado para todas as outras turmas do curso de Sistema de Informações para
assim aumentar a os dados da tabela de profissionais, porquanto estava apenas para
algumas pessoas do curso, após o término da coleta de dados será aplicada a
metodologia e o algoritmo K-means, resultando nos dashboards, com informações
relevantes.</p>

## Referências Bibliográficas
<p>AGARWAL, Deepak. Publicidade computacional: o jeito do LinkedIn. 2013. Disponível
em <https://dl.acm.org/doi/abs/10.1145/2505515.2514690> Acesso em: 7 Out 2021</p>
<p>AHMED, SERAJ e ISLAM, Mohiuddin Ahmed, Raihan Seraj e Syed Mohammed Shamsul
Islam. O Algoritmo k-means: Uma Pesquisa Abrangente e Avaliação de
Desempenho. Eletrônica 2020, Disponivel em:
<https://doi.org/10.3390/electronics9081295> Acesso em: 12 Mai 2022</p>
<p>ALMEIDA e PINHO, Maria Elisa Grijó Guahyba e Luís Ventura. Adolescência, família e
escolhas: implicações na orientação profissional. 2008. Disponível em
<https://www.scielo.br/j/pc/a/VbGsdYdh6fCxv7WpkX3S9Lr/?format=pdf&lang=pt>. Acesso
em: 9 Out 2021.</p>
<p>AMO, Sandra de. Técnicas de Mineração de Dados. Universidade Federal de
Uberlândia Faculdade de Computação. Uberlândia, 2006.
Assis, Mariela CS Fontenelle Silly de. Motivações para transição de carreira na área de
tecnologia da informação: uma abordagem Delphi. Dissertação 2016.</p>
<p>BRUNO ANASTACIO, K-means: o que é, como funciona, aplicações e exemplo em
Python. 2020. Disponível em < K-means: o que é, como funciona, aplicações e exemplo
em Python | by Bruno Anastacio>. Acesso em: Out 2021</p>
<p>BONEL, Claudio. Power BI Black Belt. Rio de Janeiro,2019
DATE, C.J. Introdução a sistemas de banco de dados. Rio de Janeiro: Elsevier, 2004.</p>
<p>CASTRO e FERRARI, Leandro Nunes e Daniel Gomes. Introdução à mineração de
dados: conceitos básicos, algoritmos e aplicações. São Paulo: Saraiva,2016.</p>
<p>FAYYAD, PIATETSKY-SHAPIRO E SMITH, Usama Fayyad, Gregory Piatetsky-Shapiro e
Padhraic Smyth. From Data Mining to Knowledge Discovery in Databases (Da
mineração de dados à descoberta de conhecimento em bancos de dados). 1996.
Disponível em:
<https://www.kdnuggets.com/gpspubs/aimag-kdd-overview-1996-Fayyad.pdf></p>
<p>HALF, Robert. Índice de Confiança Robert Half. 2021. Disponível em
<https://www.roberthalf.com.br/sites/roberthalf.com.br/files/documents_not_indexed/robert-h
alf-indice-de-confianca-16-edicao.pdf>. Acesso em 01 out 2021.</p>
<p>IBGE, Instituto Brasileiro de Geografia e Estatística. O que é desemprego. Disponível em
<https://www.ibge.gov.br/explica/desemprego.php>. Acesso em 07 Out 2021.
KARINA MOURA, Ciclo de vida dos dados. 2019. Disponível em
<https://medium.com/@kvmoura/kdd-process-9b8e3062142> Acesso em 17 Mai 2022.</p>
<p>Menezes, Nilo Ney Coutinho. Introdução à programação com Python: algoritmos e
lógica de programação para iniciantes / Nilo Ney Coutinho Menezes. -- São Paulo:
Novatec Editora, 2010.</p>
<p>OLIVEIRA e SILVA, Cássio Oliveira e João Carlos da Silva. Mineração de Dados:
Conceitos, Tarefas, Métodos e Ferramentas. São Paulo, 2009.</p>
<p>OSMAN, Abdullahi Sidow Osman.Técnicas de mineração de dados. Faculdade de
Computação e Tecnologia da Informação, Al-Madinah International University (MEDIU),
Malásia. 2019</p>
<p>PINHEIROS, Sofia Alexandra Santos. Potencialidades do Power BI Desktop na
Análise Preditiva. Católica Porto Business Scholl. Portugal, 2020.</p>
<p>PIRES, RAMOS e NEGRETTO, Diego Luís Pires, Júlio César Ramos, Diego Henrique
Negretto. Aplicação de técnicas de Machine Learning na previsão de Evasões em
Universidade Particular. 2021. Centro Universitário Hermínio Ometto - UNIARARAS,
Araras – SP, Brasil</p>
<p>PYTHON. Documentação, Disponível em <https://www.python.org/about/>. Acesso 14
Mai 2022</p>
<p>QUONIAM, Luc. Inteligência obtida pela aplicação de data mining em base de teses
francesas sobre o Brasil, Disponível em<
https://www.scielo.br/j/ci/a/pRwRJKf755sZ3mdqJVg3GCB/?format=pdf&lang=pt >. Acesso
em 12 maio 2022</p>
<p>REIS, Maurício Cortez. Como as condições do mercado de trabalho influenciam as
transições do desemprego para o emprego?.2019. Disponível em
<https://www.econstor.eu/bitstream/10419/211439/1/1669569896.pdf> Acesso em: 8 Out
2021.</p>

***
