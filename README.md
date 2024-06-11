# Pose Estimation

A partir do dataset [fornecido](https://drive.google.com/drive/folders/1xxm6ZjfsDSmv6C9JvbgiGrmHktrUjV5x), realizamos uma breve análise exploratória e implementamos pose estimation a partir dos keypoints fornecidos. 

# Análise Exploratória

A análise exploratória é fundamental para entender a estrutura e a distribuição dos dados, identificar padrões e possíveis outliers, além de guiar as etapas subsequentes do processamento de dados e modelagem.

## Distribuição de Classes 

Neste trecho do código, carregamos as anotações do dataset e contamos a quantidade de imagens para cada categoria de animais. Em seguida, visualizamos a distribuição das categorias com um gráfico de barras, que nos ajuda a entender a representatividade de cada classe no dataset.

![Distribuição das categorias](/img/download-36.png). 

# Pose Estimation

A pose estimation é uma técnica utilizada para identificar e localizar pontos-chave (keypoints) no corpo dos animais a partir das imagens. Esses pontos-chave são usados para entender a posição e orientação do animal. No código, filtramos as imagens para incluir apenas bovinos, extraímos e plotamos os keypoints sobre as imagens para visualizar a pose dos animais.

Abaixo seguem alguns exemplos de imagens:

![Imagem de exemplo 1 com pose estimation](/img/download-32.png)
![Imagem de exemplo 2 com pose estimation](/img/download-33.png)
![Imagem de exemplo 3 com pose estimation](/img/download-34.png)
