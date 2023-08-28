#GIT TUTORIAL DE UMA MINA MUITO FODA 

https://github.com/rafaballerini/GitTutorial

# PROJETO FRONT-END GRUPO 4D

Primeiro encontro com o "cliente">

Empresa Nimbus Meteorologia, criada em 2020.
Desafio proposto pelo centro de operações do RJ: Monitora a meteorologia (previsão e impacto de chuvas)

Aprimorar a previsão de chuvas principalmente para a malha rodoviaria, precisão para ajudar não só dentro da cidade mas também para o mercado de construção civil (obras na via, em lagos).

Plataforma: absorve os dados meteorologicos como radares que monitoram as nuvens em tempo real; dados de raios, descarga eletrica, dados de estações, vento/chuva, umidade, localização da obra, cronograma para a tomada de decisão para fornecer previsões por equações fisicas e matemáticas para facilitar o planejamento da obra.

Solução Cronos:
Página de mapa para previsão por área, previsão em grafico, alertas, gps e radares.

Histórico de dados:
Armazena no banco de dados para depois serem recuperados por uma API e exportados em formato de arquivo de tabela.

1. Histórico de dados>
Armazena no banco de dados para depois serem recuperados por uma API e exportados em formato de arquivo de tabela. Desafio: Novo histórico de dados e CRIAR uma página mais robusta que disponibilize dados nessa forma:

Tabelas, Gráficos (lineares, barras e vetores);
Marcadores Georeferenciados em um mapa;
Botões para exportação para csv, pdf e png;
Interação entre os componentes;
Adaptação para mobile ((((((((MOBILE FIRST)))))))).

2. Requisição de dados>
Deve ser feita através de um formulário que ira considerar uma serie de critérios como filtro, com data inicial, data final, tipo de variavel meteorologica, estação ou ponto de monitoramento, frequência e operação matemática utilizada.
    Chegar até a requisição da API.

3. Mapa interativo>
Com marcadores para cada ponto de monitoramento ou estação, preenchimento de cor de acordo com critérios de criticiedade, retorno do histórico de um ou mais pontos mediante a interação com o marcador, seja utilizando poligonos para selecionar um ou mais pontos, ou seja através de um click individual.

4. Gráfico mais estéticamente organizado (noob friendly)
Dinâmicos, adaptados a frequência temporal (eixo horizontal) ordem de grandeza (eixo vertical) so yipo de variavel exibida, interagir com o gráfico e selecionar quais variaveis são exibidas simultaneamente. Apresentar uma otimização estética em termos de desempenho, responsividade e intuitividade.

SER EXPORTAVEL PARA CSV e PDF.

# Perguntas feitas ao cliente>

Atualmente a demanda em RJ, SP e CURITIBA
IDEIA: Mapa tenha foco em uma estação em especifico (o usuário escolha a que quiser)

Quem usa o sistema normalmente? pessoas/principalmente empresas que contratam o serviço (setores de planejamento, engenheiro, meteorologistas)

Quais serão os dados? As estações tem sensores diferentes com medidas e semanticas diferentes a quantidade de variáveis são muinto grandes.

Eles darão dados "mentirosos" para podemos trabalhar com o projeto.