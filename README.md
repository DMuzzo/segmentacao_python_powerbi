# segmentacao_python_powerbi
A segmentação envolve várias etapas que permite dividir e organizar conjuntos de dados de forma eficiente para análise e processamento. 
Aqui estão os principais processos utilizados:

Importação de Dados: 
  A primeira etapa consiste em importar os dados para o ambiente do Google Colab.
  
Pré-processamento: 
  Antes de segmentar, é necessário limpar e preparar os dados. Isso pode incluir a remoção de valores ausentes, normalização de dados, conversão de tipos de dados e outras transformações necessárias para garantir que os   
  dados estejam prontos para análise. Nesse caso, não foi necessario realizar a limpeza dos dados pois já estava pronto para uso. 

Divisão do Conjunto de Dados: 
  A segmentação será utilizando bibliotecas como pandas, KMeans, sklearn.cluster e sklearn.preprocessing. 
  Nessa etapa para é foi necessario padronizar os dados com o KMeans.

Análise Exploratória: 
Uma vez segmentados, os dados podem ser analisados separadamente para identificar padrões, tendências e insights específicos para cada segmento. Nessa exemplo a segmentação foi de três(3) grupos separando em 0, 1 e 2 grupos. 

Armazenamento e Exportação: 
  O dado segmentado foi salvo no proprio google colab e feito o download separadamente. 

  ANÁLISE COM POWER BI 
No power BI, foi feito o tratamento dos dados, modificando o valor do grupo para deixa-lo visualmente melhor, logo em seguida foi modificado o tipo de cada coluna, valor monetário, int, e texto. 
Após todos os processo primarios, chega a hora da montagem dos graficos, onde foi criado filtros de grupos, idade e renda anual. 
Um dos graficos mais importantes criados para esse caso, é o grafico de dispersão, podendo perceber a segmentação de forma visual e até o limite de onde foi feito a separação de cada grupo. 
