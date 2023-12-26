<h1 align="center">Análise do Google Trends 2003-2022</h1>

Este projeto em R realiza uma análise dos dados do Campeonato Brasileiro de 2003 a 2022, disponíveis no Kaggle. A análise inclui a visualização de gols marcados por ano e por estado, utilizando mapas para mostrar a distribuição geográfica dos gols.
<br>
<br>
Através da análise dos picos de busca do termo "Guerra, Hamas e Onu" ao longo ano de 2023, pretendo obter insights sobre o interesse do tema entre os brasileiros. Utilizaremos os dados fornecidos pelo Google Trends para identificar os momentos em que houve um aumento significativo nas pesquisas relacionadas a esses temas, permitindo uma compreensão mais aprofundada do impacto desses eventos e conquistas em sua visibilidade e popularidade.
<br>

**Distribuição do gols por Estado & Ano da competição:**
<br>
![image](https://github.com/rddamasceno/resultados_brasileirao_r/assets/55591959/680aa26b-b59c-48a8-80fb-43430c2a92d8)

<h2 align="left">🔎 Descobertas:</h2>

 - O futebol paulista é o mais dominante no Campeonato Brasileiro.
 - O Espírito Santo é o único estado do Sudeste que não tem representantes na elite do futebol brasileiro.
 - Os rebaixamentos são bastante movimentados, com times de diferentes estados alternando entre as séries A e B. Bahia, Mato Grosso e Goiás são alguns dos estados que mais caíram para a Série B.
 - O futebol brasileiro é uma paixão nacional e é praticado em quase todas as regiões do país. A região Sul é a que sempre teve representantes na Série A, com exceção de 2020, quando o Criciúma foi rebaixado para a Série B. Isso evidencia a força do futebol nessa região.
 - Nos anos de 2003 a 2005, 2020, 2014 e 2018, houve menos gols do que no campeonato anterior, com uma média de 0,15 gols a menos por partida.
 - A edição de 2021, com uma média de 2,95 gols por partida, foi a que teve mais gols nos últimos 16 anos, desde 2005, quando foram marcados 1.451 gols, com uma média de 3,13 gols por partida.
 - Os cinco estados com mais gols são: SP, RJ, RS, MG, PR.

<h2 align="left"> 🛠️ Ferramentas:</h2>

**Visualização de Dados:**

 - **ggplot2:** É a principal biblioteca para a criação de gráficos elegantes no R. Ela utiliza a Gramática de Gráficos, uma estrutura que permite construir gráficos de maneira personalizada.

**Manipulação de Dados:**

 - **data.table:** Oferece um framework para a criação de tabelas de dados de alto desempenho, com foco na velocidade e eficiência em operações como filtragem, agrupamento e junção de grandes conjuntos de dados.
 - **dplyr:** Proporciona uma gramática concisa e intuitiva para a manipulação de dados, facilitando operações comuns como seleção, filtragem, organização, criação de novas variáveis e resumo de dados.
 - **tidyr:** É especializada na transformação de dados para formatos "tidy", onde cada linha representa uma observação e cada coluna uma variável, tornando os dados mais organizados e fáceis de trabalhar com outras bibliotecas.
   
**Análise Espacial:**

 - **sf:** Permite a leitura, escrita, manipulação e análise de dados geoespaciais no R, trabalhando com diferentes tipos de geometrias (pontos, linhas, polígonos) e sistemas de coordenadas.

**Escalas de Cores:**

 - **viridis:** Fornece uma coleção de escalas de cores perceptualmente uniformes, projetadas para serem visualmente agradáveis e garantir a distinção de diferentes valores de dados, especialmente para pessoas com deficiência visual.


