# Exercício Workflows Git

Utilizaremos uma amostra dos dados de 2006 do dataset: [Data Expo 2009: Airline on time
data](https://doi.org/10.7910/DVN/HG7NV7).

Utilize esse [link](data/2006-sample.csv) para baixar o arquivo csv.

Uma descrição dos dados presentes no dataset pode ser encontrada nesse
[link](http://stat-computing.org/dataexpo/2009/the-data.html).

Em duplas, utilizar o workflow de *feature branch* e escrever códigos em `bash script` para resolver os seguintes problemas.


Para cada *feature*, uma *issue* precisa ser aberta. A issue deve ser assinalada a um dos componentes da dupla. O *pull request* com a implementação da feature deve fechar a *issue* relacionada. Por favor verificar [essa referência](https://docs.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword) sobre como relacionar uma *issue* a um *pull request*.

## Features

1. Descobrir a quantiade de atrasos de uma dada companhia passada como parâmetro. Consultar [essa referência](https://tecadmin.net/tutorial/bash-scripting/bash-command-arguments/) sobre como criar e receber parâmetros em um script bash.


1. Descobrir o vôo com maior atraso na chegada (`ArrDelay`) registrado.

1. Descobrir o vôo com maior atraso na saída (`DepDelay`) registrado.

1. Descobrir o vôo mais longo.

1. Contar quantos vôos precisaram ser redirecionados (`Diverted`).

1. Utilizando a dica [nessa resposta](https://stackoverflow.com/a/3096575), calcular o tempo de atraso total para a companhia `Delta Air Lines`. Não esquecer de filtrar linhas com dados faltando e também com valores negativos (casos em que os vôos são adiantados) 

1. Mostrar o tempo total de atrasos para a decolagem de vôos no aeroporto `JFK`, de Nova Iorque.

1. Mostrar o tempo total de atrasos para pousos no `Aeroporto Internacional de Los Angeles`.

##### Bonus
Utilizar a referência no [link](https://stackoverflow.com/a/1521498), para construir scripts que implementem as seguintes funcionalidades:

1. Listar qual companhia teve o maior tempo total de atrasos (atrasos somente na decolagem).

1. Listar qual aeroporto teve o maior tempo total de atrasos (atrasos somente na decolagem).

