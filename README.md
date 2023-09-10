# Grupo-4D

# PROJETO FRONT-END GRUPO 4D

## Primeiro encontro com o "cliente">

Empresa Nimbus Meteorologia, criada em 2020.
Desafio proposto pelo centro de operações do RJ: Monitora a meteorologia (previsão e impacto de chuvas)

Aprimorar a previsão de chuvas principalmente para a malha rodoviaria, precisão para ajudar não só dentro da cidade mas também para o mercado de construção civil (obras na via, em lagos).
### O que a plataforma faz?
Ela absorve os dados meteorologicos como radares que monitoram as nuvens em tempo real; dados de raios, descarga eletrica, dados de estações, vento/chuva, umidade, localização da obra, cronograma para a tomada de decisão para fornecer previsões por equações fisicas e matemáticas para facilitar o planejamento da obra.

Solução Cronos:
Página de mapa para previsão por área, previsão em grafico, alertas, gps e radares.

## Pontos a serem melhorados:
Histórico de dados:
Armazena no banco de dados para depois serem recuperados por uma API e exportados em formato de arquivo de tabela.

1. **Histórico de dados**>
Armazena no banco de dados para depois serem recuperados por uma API e exportados em formato de arquivo de tabela. Desafio: Novo histórico de dados e CRIAR uma página mais robusta que disponibilize dados nessa forma:

- Tabelas, Gráficos (lineares, barras e vetores);
- Marcadores Georeferenciados em um mapa;
- Botões para exportação para csv, pdf e png;
- Interação entre os componentes;
- Adaptação para mobile (MOBILE FIRST).

2. **Requisição de dados**>
Deve ser feita através de um formulário que ira considerar uma serie de critérios como filtro, com data inicial, data final, tipo de variavel meteorologica, estação ou ponto de monitoramento, frequência e operação matemática utilizada.
    Chegar até a requisição da API.

3. **Mapa interativo**>
Com marcadores para cada ponto de monitoramento ou estação, preenchimento de cor de acordo com critérios de criticiedade, retorno do histórico de um ou mais pontos mediante a interação com o marcador, seja utilizando poligonos para selecionar um ou mais pontos, ou seja através de um click individual.

4. **Gráfico mais estéticamente organizado** (noob friendly)
Dinâmicos, adaptados a frequência temporal (eixo horizontal) ordem de grandeza (eixo vertical) ao tipo de variavel exibida, interagir com o gráfico e selecionar quais variaveis são exibidas simultaneamente. Apresentar uma otimização estética em termos de desempenho, responsividade e intuitividade.

**>>>SER EXPORTAVEL PARA CSV e PDF<<<**.

## Requisitos Funcionais:

RF1 - O sistema deverá absorver e apresentar os dados meteorológicos
e as equações matemáticas e físicas necessárias na tela principal.

RF2 - Os dados serão atualizados em tempo real

RF3 - Na area superior da tela, o sistema deve apresentar 4 abas,
página principal, histórico de dados, requisição de dados e o mapa

RF4 - Na aba histórico de dados, os dados serão armazenados para 
poderem ser posteriormente recuperados

RF5 - Os dados devem ser apresentados através de tabelas, gráficos 
(lineares, barras e vetores) e marcadores georeferenciados em um mapa.

# 5W2H



