# Introdução 

- [O que é Inteligência Artificial](#o-que-e-inteligencia-artificial)
- [Machine Learning](#machine-learning)
  - [Tarefas de ML](#tarefas-de-ml)
- [Machine Learning vs Deep Learning](#machine-learning-vs-deep-learning)
- [Resumo](#resumo)

<a name="o-que-e-inteligencia-artificial"></a>
## O que é Inteligência Artificial 

Inteligência artificial (IA) é um campo da ciência da computação que se dedica a criar programas de computador ou máquinas que são capazes de realizar tarefas que, normalmente, requerem a inteligência humana. Isso inclui coisas como reconhecer fala, aprender, planejar, resolver problemas e entender linguagem natural.

Imagine que você tenha um robô que pode aprender a identificar seu gato de estimação apenas observando-o, ou um serviço de e-mail que consegue filtrar spam sem que você tenha que ensiná-lo explicitamente o que é spam. Isso é possível por causa da IA, que permite que as máquinas "aprendam" com experiências e melhorem ao longo do tempo.

A IA é como uma receita de bolo muito avançada que dá ao computador os passos para fazer algo. Às vezes, a receita pode se ajustar baseada no que funcionou ou não, melhorando a si mesma. É uma mistura de matemática, estatística e regras que dão ao computador a capacidade de tomar decisões sem ser explicitamente programado para cada situação específica.

<a name="machine-learning"></a>
## Machine Learning

Machine Learning, ou aprendizado de máquina, é uma subárea da inteligência artificial (IA) que se concentra no desenvolvimento de algoritmos e técnicas que permitem aos computadores aprenderem padrões a partir de dados. Em outras palavras, em vez de serem explicitamente programados para realizar uma tarefa específica, os sistemas de Machine Learning são treinados usando grandes volumes de dados para reconhecer padrões e fazer previsões ou tomar decisões com base nesses padrões. Existem várias técnicas de Machine Learning, como regressão, classificação, agrupamento, entre outras.

![Machine Learning](https://github.com/antonioanerao/estudo-machine-learning/blob/main/img/ml.png?raw=true)

<a name="tarefas-de-ml"></a>
### Tipos de tarefas de ML

No campo de Machine Learning (ML), existem vários tipos de tarefas que os algoritmos de ML podem realizar. Cada tipo de tarefa tem um objetivo específico e requer abordagens e algoritmos diferentes. Aqui estão alguns dos tipos de tarefa mais comuns em ML

**Classificação**:
- **Objetivo**: Classificar os dados em categorias ou classes predefinidas.
- **Exemplo**: Classificar e-mails como spam ou não spam, identificar se uma imagem contém um gato ou um cachorro.
- **Algoritmos populares**: Regressão Logística, Support Vector Machines (SVM), Árvores de Decisão, Redes Neurais.

**Regressão**:
- **Objetivo**: Prever um valor contínuo com base em entradas.
- **Exemplo**: Prever o preço de uma casa com base em características como tamanho, número de quartos, etc.
- **Algoritmos populares**: Regressão Linear, Regressão de Árvore de Decisão, Regressão de Floresta Aleatória.

**Agrupamento**:
- **Objetivo**: Agrupar dados semelhantes em grupos ou clusters.
- **Exemplo**: Agrupar clientes com base em seu comportamento de compra para segmentação de mercado.
- **Algoritmos populares**: K-Means, DBSCAN, Agrupamento Hierárquico.

**Aprendizado por Associação**:
- **Objetivo**: Descobrir regras que descrevem associações frequentes entre itens em um conjunto de dados.
- **Exemplo**: Recomendação de produtos com base nas compras anteriores dos clientes.
- **Algoritmos populares**: Apriori, Eclat.

**Processamento de Linguagem Natural (NLP)**:
- **Objetivo**: Compreender e processar texto natural.
- **Exemplo**: Análise de sentimentos em tweets, tradução automática, chatbots.
- **Algoritmos populares**: Redes Neurais Recorrentes (RNNs), Transformers.

**Aprendizado por Reforço**:
- **Objetivo**: Treinar um agente para tomar ações sequenciais em um ambiente para maximizar uma recompensa cumulativa.
- **Exemplo**: Treinar um robô para jogar xadrez ou um carro autônomo para dirigir.
- **Algoritmos populares**: Q-Learning, Deep Q-Networks (DQN), A3C.

**Detecção de Anomalias (Outlier Detection)**:
- **Objetivo**: Identificar padrões incomuns ou anômalos nos dados.
- **Exemplo**: Detectar fraudes em transações financeiras, identificar falhas em sistemas industriais.
- **Algoritmos populares**: Isolation Forest, Uma-Class SVM.

**Redução de Dimensionalidade**:
- **Objetivo**: Reduzir a complexidade de dados mantendo as informações mais relevantes.
- **Exemplo**: Visualização de dados de alta dimensão, acelerar o treinamento de modelos.
- **Algoritmos populares**: Análise de Componentes Principais (PCA), t-SNE.

> **Note**
> Cada tipo de tarefa tem seus próprios desafios e abordagens específicas. A escolha do tipo de tarefa depende dos dados e do problema que você está tentando resolver. É importante compreender esses tipos de tarefa para selecionar a abordagem correta ao aplicar ML a um problema específico.

<a name="machine-learning-vs-deep-learning"></a>
## Machine Learning vs Deep Learning 

Deep Learning é uma subárea específica do Machine Learning que utiliza redes neurais artificiais profundas para aprender padrões complexos a partir de grandes conjuntos de dados. O termo "profundo" refere-se ao fato de que essas redes neurais têm muitas camadas (também conhecidas como arquiteturas profundas), o que lhes permite aprender representações de dados em diferentes níveis de abstração. As redes neurais profundas são particularmente eficazes em tarefas que envolvem dados não estruturados, como imagens, áudio e texto.

<a name="resumo"></a>
## Resumo 

Em resumo, todos os Deep Learning são Machine Learning, mas nem todo Machine Learning é Deep Learning. O Deep Learning é uma técnica mais avançada e complexa que se tornou popular devido aos avanços tecnológicos e ao aumento da disponibilidade de grandes conjuntos de dados e poder computacional. Ele é frequentemente usado em reconhecimento de imagens, processamento de linguagem natural, tradução automática, entre outras aplicações que envolvem dados complexos e não estruturados. O Machine Learning, por outro lado, é uma área mais ampla que inclui várias técnicas, incluindo o Deep Learning, para ensinar os computadores a aprender com os dados e melhorar seu desempenho em tarefas específicas.
