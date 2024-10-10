# Projetos de Machine Learning e Redes Neurais
Este repositório contém dois projetos distintos focados em Redes Neurais e Deep Learning, aplicando diferentes arquiteturas e abordagens em problemas variados de classificação.

## Projetos
Previsão de Falhas Cardíacas com Data Augmentation e Redes Neurais
Inception V1 (GoogLeNet) aplicado ao Fashion MNIST
# 1. Previsão de Falhas Cardíacas com Data Augmentation e Redes Neurais
## Descrição
Este projeto visa prever falhas cardíacas usando um dataset médico e técnicas de Data Augmentation para balanceamento de classes, além de aplicar uma Rede Neural densa em TensorFlow para o treinamento e validação do modelo.

## Dataset
O dataset utilizado contém informações clínicas de pacientes, com uma variável alvo indicando se ocorreu ou não uma falha cardíaca.

## Requisitos
Python 3.x
TensorFlow
NumPy
Pandas
Matplotlib
## Estrutura do Código
data_preprocessing.py: Processamento e balanceamento dos dados.
model.py: Definição, compilação e treinamento da Rede Neural.
evaluation.py: Avaliação do modelo e geração de métricas de desempenho.
## Como Usar
### Instale os requisitos:
bash
Copiar código
pip install -r requirements.txt
### Execute o script de preprocessamento dos dados:
bash
### Copiar código
python data_preprocessing.py
### Treine o modelo:
bash
Copiar código
python model.py
Avalie o desempenho:
bash
Copiar código
python evaluation.py
## Arquitetura
O modelo consiste em uma Rede Neural densa com várias camadas ocultas, que realiza a previsão com base nos dados clínicos dos pacientes. As técnicas de Data Augmentation foram aplicadas para lidar com o desbalanceamento das classes no dataset.

# 2. Inception V1 (GoogLeNet) aplicado ao Fashion MNIST
## Descrição
Este projeto aplica a arquitetura Inception V1 (GoogLeNet) para classificar imagens do dataset Fashion MNIST, que contém 70.000 imagens de roupas e acessórios em 10 categorias.

## Dataset
O Fashion MNIST é um dataset de imagens em escala de cinza com 28x28 pixels, onde cada imagem pertence a uma de 10 classes, como camisetas, calças, sapatos, etc.

## Requisitos
Python 3.x
TensorFlow
Keras
NumPy
Matplotlib
## Estrutura do Código
inception_model.py: Definição da arquitetura Inception V1 em TensorFlow.
train.py: Treinamento do modelo com o dataset Fashion MNIST.
evaluate.py: Avaliação e geração de métricas de precisão para o modelo.
## Como Usar
Instale os requisitos:
bash
Copiar código
pip install -r requirements.txt
## Execute o treinamento:
bash
Copiar código
python train.py
### Avalie o modelo:
bash
Copiar código
python evaluate.py
## Arquitetura
O modelo Inception V1 permite realizar convoluções em várias escalas simultaneamente, tornando-o ideal para a classificação de imagens com diferentes níveis de detalhe. A arquitetura foi originalmente desenvolvida para o desafio ImageNet e é aplicada aqui para classificar as imagens do Fashion MNIST.
Contribuições são bem-vindas! Se você deseja contribuir, siga os passos:

Faça um fork do projeto.
Crie uma nova branch (git checkout -b feature/nova-funcionalidade).
Commit suas mudanças (git commit -m 'Adiciona nova funcionalidade').
Envie para o repositório remoto (git push origin feature/nova-funcionalidade).
Abra um Pull Request.

