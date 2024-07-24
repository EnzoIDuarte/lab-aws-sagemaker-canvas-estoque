# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

Para realização desse projeto, foi utilizado um Dataset próprio do Amazon SageMaker (canvas-sample-retail-electronics-forecasting.csv). Este Dataset foi importado para a criação do modelo. Dataset.JPG


### 2. Construir/Treinar

Para a construção do modelo foi utilizado Item_ID como identificador primário dos itens presentes no dataset. O modelo visa prever a demanda relacionada a determinado produto. Logo, a coluna "Target" selecionada foi a coluna demanda, agrupando pela coluna "Price". Build.JPG

### 3. Analisar

Com relação a fase de análise, foi identificado que as métricas se aproximam do valor 0, demonstrando que o dataset utilizado apresenta uma boa consistência. Analyze.JPG

### 4. Prever

Para a fase de previsão, foram testados os itens com determinados valores, visando identificar os preços ideais para determinado item. Predict.JPG

## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.
