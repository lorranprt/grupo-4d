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

# 5W2H
1. **O que?** R: Ela absorve os dados meteorologicos como: radares que monitoram as nuvens em tempo real.
2. **Por que?** R: Para fornecer previsões por equações físicas e matemátcias para facilitar o planejamento da obra.
3. **Quem?** R: Pessoas/Principalmente empresas que contratam o serviço (setores de planejamento, engenheiro, 
meteorologistas)
4. **Quando?** R: A entrada de dados é feita o tempo todo. Porém a consulta do cliente depende do horário desejado, seja 24H direto ou um planejamento programado.
6. **Como?** R: Será feita uma requisitação de dados através de um formulário feita pelo usuário, os dados serão recuperados através de uma API e após isso será exportado no formato de arquivo de tabela.
5. **Onde?** R: As informações sobre onde cada um dos procedimentos será executado vai ser econtrado no próximo tópico que se referem aos **Requisitos Funcionais**.

# Requisitos Funcionais:

- **RF1:** O sistema deverá absorver e apresentar os dados meteorológicos e as equações matemáticas e físicas necessárias na tela principal. 
- **RF2:** Os dados serão atualizados em tempo real 
- **RF3:** Na área superior da tela, o sistema deve apresentar 2 abas, página principal e histórico de dados
- **RF4:** Na aba histórico de dados, os dados serão armazenados para poderem ser posteriormente recuperados 
- **RF5:** Os dados devem ser apresentados através de tabelas, gráficos (lineares, barras e vetores) e marcadores georreferenciados em um mapa. 
- **RF6:** Na parte superior da tela será reservada para o requisito de dados através de um formulário. 
- **RF7:** Esse formulário irá considerar uma série de critérios de filtro, com data inicial, data final, tipo de variável meteorológica, estação ou ponto de monitoramento, frequência e operação matemática utilizada. 
- **RF8:** No centro da tela terá um gráfico interativo. 
- **RF9:** O gráfico será dinâmico e adaptará a frequência temporal, representada no eixo horizontal, e a ordem de grandeza no vertical, ao tipo de variável exibida 
- **RF10:** Na parte superior do gráfico terá uma opção para selecionar quais variáveis serão exibidas. 
- **RF11:** Na parte inferior à esquerda da tela terá o mapa interativo com marcadores para cada ponto de monitoramento ou estação. 
- **RF12:** Os marcadores terão cores de acordo com a situação meteorológica do local.
- **RF13:** O usuário pode interagir com os marcadores para obter mais informações do local.
- **RF14:** Essa interação pode ser feita através de um único clique ou a ferramenta de polígono para selecionar um ou mais marcadores
- **RF15:** Na parte inferior à direita da tela terá a tabela com as informações da área selecionada.
- **RF16:** O usuário será capaz de exportar todas essas informações para os formatos CSV, PDF e PNG
- **RF17:** O botão para exportação se encontrará logo acima do recurso desejado, ou seja, se o usuário deseja gerar um PNG do mapa, deverá procurar o botão logo acima do mapa

# Requisitos não-funcionais:

1. Usabilidade
	- US1: O software deve ser confiável, e ter o mínimo de falhas possível, não apresentando erros na maioria das vezes que for utilizado.
2. Confiabilidade
	- CF1: Só é aceitável uma pequena porcentagem de falhas.
3. Portabilidade
	- PR1: O software deverá ter acessibilidade para mobile.
	- PR2: O site deverá ser totalmente responsivo.



