# python_selenium_webscraper01
  Utilizando Python e o Selenium webdriver capturo os preços do bitcoin dos últimos 3 anos da página da Coin Market Cap.
  O algoritmo efetua os cliques no calendário para a escolha da faixa de datas para exibição dos preços históricos da criptomoeda Bitcoin
e posteriormente clica nos botões "Load More" para expandir a exibição dos dados na tela até a dada final para que se possa capturar
todos os dados requeridos.
  Após a captação dos dados, efetua-se a criação de um dataframe com as colunas e as linhas "raspadas" do site da coin market cap.
Por fim, os dados são transformados em string para que se retire os colchete que envolvem cada dado.
