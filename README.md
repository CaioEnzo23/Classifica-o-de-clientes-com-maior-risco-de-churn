# Classificação de clientes com maior risco de churn

Este projeto foi criado com o intuito de aprimorar minhas habilidades em Python utilizando um modelo de Machine Learning. 

Este projeto visa analisar a taxa de rotatividade de clientes em um banco, compreendendo as razões subjacentes à saída dos clientes. O objetivo é desenvolver um Modelo de Machine Learning capaz de identificar os principais fatores que influenciam significativamente a rotatividade de clientes. Ao final, selecionaremos o modelo mais confiável, atribuindo uma probabilidade de rotatividade, aprimorando o serviço de atendimento ao cliente para minimizar esforços na prevenção da rotatividade e direcionando ações específicas para reter os clientes.

Através da análise de dados, descobri insights valiosos e treinei um modelo de aprendizado de máquina capaz de prever o churn. 

Portanto separei este projeto em 6 partes :

#  Importação de Bibliotecas e Conjunto de Dados

- Importei as bibliotecas necessárias, como pandas, numpy e matplotlib.
- Carreguei o conjunto de dados contendo informações sobre clientes e sua interação com a empresa.

![image](https://github.com/user-attachments/assets/8244940d-6c77-4543-b5f6-1a9923a0426e)

# Tratamento dos Dados

- Explorei a estrutura do conjunto de dados, identificando tipos de variáveis e características.
- Verifiquei se havia dados duplicados.

![image](https://github.com/user-attachments/assets/2721da10-6b69-40b1-b049-397601c6af8a)

# Limpeza dos Dados

- Identifiquei e tratei os valores ausentes, usando estratégias como remoção.
- Realizei uma validação para detectar inconsistências nos dados e corrigir.

![image](https://github.com/user-attachments/assets/2c3fa5a0-2f1f-407e-8018-baabe4255094)

# Análise Exploratória de Dados (EDA)

- Tracei um gráfico de barras e um gráfico de pizza para mostrar a distribuição da rotatividade (churn) em relação aos clientes.
- Explorei gráficos e histogramas para entender a distribuição e relações entre as variáveis independentes.

![image](https://github.com/user-attachments/assets/dd60b1b4-fd19-43e7-9506-1746c2615f40)
![image](https://github.com/user-attachments/assets/03f22b26-8db2-41e6-980a-021cf74ac52a)
![image](https://github.com/user-attachments/assets/3cce2dc4-3daf-4360-9d92-3a6fd00116ae)

# Pré-processamento dos Dados

- Avaliei a relevância das variáveis para o problema de churn e selecione as mais importantes.
- Realizei transformações necessárias, normalização de variáveis categóricas.
- Separei os dados em conjuntos de treinamento e testei para avaliação do modelo.
- Apliquei a técnica de oversampling SMOTE para equilibrar as classes de rotatividade.

![image](https://github.com/user-attachments/assets/84e4a2a4-6ba0-46a0-802c-5c4ec2c48d32)
![image](https://github.com/user-attachments/assets/9212f41d-0ce6-411c-9240-79dd95ca14ca)

# Criação, Treinamento e Avaliação do Modelo

- Escolha algoritmos de classificação, como Árvore de Decisão, Random Forest ou SVM, para prever a rotatividade.
- Treine o modelo nos dados de treinamento e ajuste seus parâmetros para otimizar o desempenho.
- Avalie o modelo usando métricas como acurácia, precisão, revocação e pontuação F1.
- Interprete a matriz de confusão para entender os resultados de verdadeiros positivos, verdadeiros negativos, falsos positivos e falsos negativos.
- Trace a curva ROC e calcule a área sob a curva (AUC) para avaliar a capacidade preditiva do modelo.
- Identifique as características mais influentes na predição da rotatividade usando recursos como importância de características.

![image](https://github.com/user-attachments/assets/f2c67ce2-4078-49b7-9ee1-34d9d1902cbe)
![image](https://github.com/user-attachments/assets/15277ce2-e353-4b35-908d-db1635ed7a78)
![image](https://github.com/user-attachments/assets/d0d63f99-e63a-4fcd-a284-85424a172fbd)
