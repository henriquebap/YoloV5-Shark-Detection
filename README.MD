# Treinamento de Detecção de Objetos com YoloV5

## Introdução

Este repositório contém o código para um projeto de treinamento de um modelo YoloV5 para detectar tubarões, raias e peixes em imagens. O projeto utiliza o framework Jupyter Notebook e as bibliotecas YoloV5 e Roboflow.

## Objetivos

Os objetivos do projeto são:

- Treinar um modelo YoloV5 preciso e eficiente para detecção de objetos em imagens marinhas.
- Fornecer um modelo pronto para uso para detecção de tubarões, raias e peixes em imagens.
- Facilitar a replicação e adaptação do modelo para outras tarefas de detecção de objetos.

## Pré-requisitos

Para executar este projeto, você precisará de:

- Computador com placa de vídeo (GPU) recomendada.
- Python >= 3.6
- PyTorch >= 1.8
- YoloV5
- Roboflow

## Como Começar

- Clone o repositório:

  - git clone [https://github.com/henriquebap/YoloV5-Shark-Detection.git](https://github.com/henriquebap/YoloV5-Shark-Detection.git)

- Instale as dependências:

  - pip install -r requirements.txt

- Baixe o dataset:
- Descompacte o dataset:
- Execute o notebook:

## Estrutura do Projeto

O projeto é organizado da seguinte maneira:

- data/: Diretório que contém o dataset de imagens.
- models/: Diretório onde os modelos treinados serão salvos.
- notebooks/: Diretório que contém o notebook Jupyter com o código de treinamento.
- requirements.txt: Arquivo que lista as dependências do projeto.
- README.md: Este arquivo com informações sobre o projeto.

O notebook irá guiar você pelas etapas do processo de treinamento, incluindo:

- Carregamento e pré-processamento do dataset.
- Definição da arquitetura do modelo YoloV5.
- Treinamento do modelo usando um algoritmo de otimização.
- Avaliação do desempenho do modelo em um conjunto de dados de validação.
- Salvamento do modelo treinado.

## Uso do Modelo Treinado

O modelo treinado pode ser usado para detectar objetos em novas imagens.

## Contato

Se você tiver dúvidas ou sugestões sobre este projeto, sinta-se à vontade para entrar em contato comigo através do e-mail:

E-mail: henriquebaptista2003@gmail.com

Agradeço sua contribuição!

## Contribuições

Este projeto é de código aberto e você é bem-vindo para contribuir! Se você tiver ideias para melhorar o projeto, ou se quiser ajudar a corrigir bugs, por favor, envie um pull request no Github.

Para contribuir:

1. Crie um fork deste repositório no seu Github.
2. Faça as alterações desejadas no seu fork.
3. Envie um pull request para este repositório.

Agradecemos sua contribuição!

## Inspiração e Créditos

Este projeto foi inspirado e parcialmente baseado nos seguintes recursos:

- Notebook Jupyter do Roboflow para treinamento de YoloV5 em dados personalizados: [Link](https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/train-yolov5-object-detection-on-custom-data.ipynb?ref=blog.roboflow.com)
- Artigo do Roboflow sobre treinamento de YoloV5 com dados personalizados: [Link](https://blog.roboflow.com/train-yolov5-classification-custom-data/)
- Plataforma Roboflow para anotação de dados: [Link](https://roboflow.com/model/yolov5)

Agradeço aos criadores desses recursos por sua valiosa contribuição para a comunidade de Deep Learning e IA.

**Observação:** É importante ressaltar que este projeto não é uma cópia direta dos recursos mencionados acima. O código foi adaptado e aprimorado para atender às minhas necessidades específicas e ao meu conjunto de dados.

Espero que este projeto seja útil para você e que sirva como inspiração para seus próprios projetos de Deep Learning e IA.
