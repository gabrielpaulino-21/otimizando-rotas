# otimizando-rotas
Automatizando rotas com Google Maps com Python

Este projeto visa otimizar o trajeto entre pontos turísticos importantes de São Paulo, utilizando Selenium (para automação de navegação) e Google Maps (para cálculo de rotas e distâncias). O objetivo principal é calcular a rota mais eficiente entre diferentes pontos, considerando o tempo de viagem e a distância. O foco é facilitar a visualização do melhor caminho para turistas ou planejadores de rotas.

Tecnologias Utilizadas:
Python: Linguagem de programação principal para automatizar o processo e manipular dados.
Selenium: Biblioteca para automação de navegação no navegador (Chrome) e interação com a interface do Google Maps.
Google Maps API: Ferramenta que fornece dados de rotas, distâncias e tempo de viagem.

Seleção de Pontos de Interesse: O projeto utiliza quatro locais turísticos de São Paulo como pontos de partida e chegada:

Mercadão de São Paulo
Catedral da Sé
Avenida Paulista
Estação da Luz
Automação da Navegação com Selenium: O Selenium é utilizado para automatizar a navegação no Google Maps. O código abre o navegador, busca os pontos no Google Maps e coleta os dados de rota.

Cálculo das Rotas: Com a integração da API do Google Maps, o script calcula a melhor rota entre os pontos listados, levando em consideração o tempo de viagem e a distância.

Otimização: O projeto pode buscar otimizar o trajeto com base em diferentes critérios, como:

Tempo mínimo de viagem.
Distância mais curta.
Evitar congestionamentos (se possível, com base em informações do Google Maps).
Resultado Final: Após calcular a melhor rota, o script pode retornar o caminho mais eficiente, exibindo a sequência de pontos com as distâncias e o tempo estimado de viagem.
