# Grupo-4D
Integrantes:

- **Lorran Porto**
- **Hannah Martins**
- **Guilherme Vallim**
- **João Gois**

# PROJETO FRONT-END GRUPO 4D

## Primeiro encontro com o cliente>

Empresa Nimbus Meteorologia, criada em 2020.
Desafio proposto pelo centro de operações do RJ: Monitora a meteorologia (previsão e impacto de chuvas)

Aprimorar a previsão de chuvas principalmente para a malha rodoviaria, precisão para ajudar não só dentro da cidade mas também para o mercado de construção civil (obras na via, em lagos).
### O que a plataforma faz?
Ela absorve os dados meteorológicos como radares que monitoram as nuvens em tempo real; dados de raios, descarga elétrica, dados de estações, vento/chuva, umidade, localização da obra, cronograma para a tomada de decisão para fornecer previsões por equações fisicas e matemáticas para facilitar o planejamento da obra.

Solução Cronos:
Página de mapa para previsão por área, previsão em gráfico, alertas, gps e radares.

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
Dinâmicos, adaptados a frequência temporal (eixo horizontal) ordem de grandeza (eixo vertical) ao tipo de variável exibida, interagir com o gráfico e selecionar quais variáveis são exibidas simultaneamente. Apresentar uma otimização estética em termos de desempenho, responsividade e intuitividade.

**>>>SER EXPORTAVEL PARA CSV e PDF<<<**.

# 5W2H
1. **O que?** R: O sistema absorve os dados meteorológicos como: radares que monitoram as nuvens em tempo real.
2. **Por que?** R: Para fornecer previsões por equações físicas e matemátcias para facilitar o planejamento da obra.
3. **Quem?** R: Pessoas/Principalmente empresas que contratam o serviço (setores de planejamento, engenheiro, meteorologistas)
4. **Quando?** R: A entrada de dados é feita o tempo todo. Porém a consulta do cliente depende do horário desejado, seja 24H direto ou um planejamento programado.
6. **Como?** R: Será feita uma requisitação de dados através de um formulário feita pelo usuário, os dados serão recuperados através de uma API e após isso será exportado no formato de arquivo de tabela.
5. **Onde?** R: Será utilizado em situações de preparação de obras e em pesquisas meteorológicas.
6. **Quanto?** R: O tempo de desenvolvimento do programador.

# Propósito do Sistema:
Apresentar os dados meteorológicos de forma organizada, para que possam ser adicionados, armazenados, editados e exportados com agilidade e facilidade, tendo um banco de dados para guardar as informações anteriores a fim de comparação e estudos. Além disso, ser adaptado para facilitar o uso e expandir os consumidores da plataforma.

# Requisitos Funcionais:

- **RF1:** O sistema deverá absorver e apresentar os dados meteorológicos e as equações matemáticas e físicas necessárias na tela principal. 
- **RF2:** O sistema deverá ter os dados atualizados em tempo real. 
- **RF3:** O sistema terá 2 abas na área superior da tela, página principal e histórico de dados.
- **RF4:** O sistema deverá ter uma aba histórico de dados, onde os dados serão armazenados para poderem ser posteriormente recuperados.
- **RF5:** O sistema terá seus dados apresentados através de tabelas, gráficos (lineares, barras e vetores) e marcadores georreferenciados em um mapa. 
- **RF6:** O sistema terá na parte superior da tela uma área reservada para o requisito de dados através de um formulário. 
- **RF7:** O sistema possuirá um formulário que irá considerar uma série de critérios de filtro, com data inicial, data final, tipo de variável meteorológica, estação ou ponto de monitoramento, frequência e operação matemática utilizada. 
- **RF8:** O sistema terá no centro da tela terá um gráfico interativo. 
- **RF9:** O sistema terá um gráfico que será dinâmico e adaptará a frequência temporal, representada no eixo horizontal, e a ordem de grandeza no vertical, ao tipo de variável exibida.
- **RF10:** O sistema terá uma parte superior do gráfico que terá uma opção para selecionar quais variáveis serão exibidas. 
- **RF11:** O sistema terá na parte inferior à esquerda da tela o mapa interativo com marcadores para cada ponto de monitoramento ou estação. 
- **RF12:** O sistema terá marcadores com cores de acordo com a situação meteorológica do local.
- **RF13:** O sistema fará com que o usuário possa interagir com os marcadores para obter mais informações do local.
- **RF14:** O sistema terá essa interação que pode ser feita através de um único clique ou a ferramenta de polígono para selecionar um ou mais marcadores.
- **RF15:** O sistema terá na parte inferior à direita da tela uma tabela com as informações da área selecionada.
- **RF16:** O sistema fará com que o usuário seja capaz de exportar todas essas informações para os formatos CSV, PDF e PNG.
- **RF17:** O sistema terá um botão para exportação que se encontrará logo acima do recurso desejado, ou seja, se o usuário deseja gerar um PNG do mapa, deverá procurar o botão logo acima do mapa.

# Requisitos não-funcionais:

- RNF1: O software deve ser confiável, e ter o mínimo de falhas possível, não apresentando erros na maioria das vezes que for utilizado.
- RNF2: Só é aceitável uma pequena porcentagem de falhas.
- RNF3: O software deverá ter acessibilidade para mobile.
- RNF4: Deverá ser feito em React.
- RNF5: O site deverá ser totalmente responsivo.

