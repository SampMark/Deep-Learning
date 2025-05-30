# Deep Learning com TensorFlow e Keras

**Bem-vindo** ao meu repositório sobre **Deep Learning com TensorFlow e Keras**!  
Aqui você encontrará diversos notebooks Colab que exploram modelagens básicas a avançadas sobre aprendizado de máquina profundo, utilizando bibliotecas Python, como o TensorFlow e o API Keras.

---

## Visão Geral sobre o TensorFlow e Keras 

O TensorFlow é uma biblioteca de código aberto criada pelo Google Brain, atualmente parte do Google DeepMind. Consolidou-se como um dos frameworks mais proeminentes para o desenvolvimento e implantação de modelos de aprendizado de máquina e Deep Learning. Desde sua criação, tornou-se indispensável em aplicações que variam de servidores robustos a dispositivos embarcados (Edge), permitindo escalabilidade e flexibilidade. A fusão com a DeepMind marca uma nova era na pesquisa em inteligência artificial, combinando recursos e expertise para enfrentar desafios avançados no campo. Acesse o artigo: [Visão Geral sobre o TensorFlow e Keras](https://docs.google.com/document/d/1Sj7wR0JEloDEdC3qa_7Mn9ZlMi7gEIsnez_agWLJD-w/edit?usp=sharing)!

Em linhas gerais, o TensorFlow oferece as ferramentas necessárias para realizar operações matemáticas complexas, para construção de arquiteturas de Redes Neurais avançadas e gerenciar o treinamento em diferentes plataformas (CPU, GPU). Por sua vez, Keras, como uma API de alto nível do TensorFlow, fornece uma interface amigável e intuitiva para realizar tarefas comuns de processamento de imagens, como classificação, aumento de dados e a implementação de técnicas mais avançadas, sem exigir um conhecimento profundo dos detalhes internos do TensorFlow.

### Breve Comparativo entre as ferramentas de Deep Learning

Comparativos com as ferramentas de _deep learning_, como PyTorch e Caffe.

| **Ferramenta** | **Vantagens**                                                                                  | **Desvantagens**                                   |
|-----------------|-----------------------------------------------------------------------------------------------|---------------------------------------------------|
| **TensorFlow**  | Flexibilidade, escalabilidade, eficiência, ampla comunidade, suporte a produção em larga escala. | Curva de aprendizado íngreme.                    |
| **Keras**       | Facilidade de uso, abstração de alto nível, modularidade, extensibilidade, integração nativa com o TensorFlow. | Menos flexível que o TensorFlow.                 |
| **PyTorch**     | Flexibilidade, facilidade de uso, popularidade na pesquisa, execução dinâmica, comunidade crescente. | Menos maduro que o TensorFlow em produção.       |
| **Caffe**       | Eficiência, popularidade em visão computacional, desempenho otimizado para inferências rápidas. | Menos flexível que TensorFlow e PyTorch.         |

**Fontes**:
- [Google DeepMind](https://deepmind.google/)
- [KERAS: Simple, Flexible and Powerful!](https://keras.io/)
- [Keras-Team: Deep Learning for humans](https://github.com/keras-team)

## 📂 Estrutura do Repositório

### **1️⃣ Funcionalidades Avançadas do Keras**
- 🔧 **Conteúdos explorados**: 
  - Uso da API funcional do Keras para criação de modelos complexos.
  - Criação de camadas e modelos personalizados, usando a lógica de Programação Orientada a Objetos (POO).
- 🧪 **Projetos**:
  - [Implementação da API funcional para a construção de Redes Neurais](https://github.com/SampMark/Deep-Learning/blob/main/Building_Neural_Networks_with_the_Keras_Functional_API.ipynb)
  - [Implementação do Dropout e BatchNormalization em Redes Neurais](https://github.com/SampMark/Deep-Learning/blob/main/Dropout_and_Batch_Normalization_in_Neural_Network.ipynb)
  - [Programação Orientada a Objetos (POO) na construção e avalição de modelos de Redes Neurais com o TensorFlow/Keras](https://github.com/SampMark/Deep-Learning/blob/main/Creating_Custom_Layers_and_Models.ipynb)

---

### **2️⃣ CNNs Avançadas no Keras**
- As Redes Neurais Convolucionais (CNNs) são modelos poderosos em tarefas de **visão computacional**, incorporam técnicas avançadas em sua construção e treinamento usando a biblioteca Keras, as quais elevam significativamente o desempenho dos modelos de aprendizado profundo em tarefas complexas. As técnicas avançadas incorporam arquiteturas de rede mais sofisticadas (além das camadas convolucionais e de _pooling_ básicas), funções de ativação não lineares mais complexas, mecanismos de regularização mais eficazes e otimizadores de treinamento avançados.
- 🖼️ **Conteúdos explorados**: 
  - Técnicas de aumento de dados e transferência de aprendizado:
  - Uso do TensorFlow para processamento de imagens.
- 🧪 **Projetos**:
  - [**Introdução às Redes Neurais Convolucionais (CNN)**, criação de uma imagem artificial simples e aplicação de várias técnicas](https://github.com/SampMark/Deep-Learning/blob/main/Convolutional_Neural_Networks.ipynb)
  - [**_Transfer Learning_**, utilização de modelo pré-treinado para classificação binária](https://github.com/SampMark/Deep-Learning/blob/main/binary_classification_model_using_transfer_learning_VGG16.ipynb)
  - [**_Transfer Learning_ para classificação de imagens de frutas**, usando o modelo VGG16 pré-treinado em ImageNet e o Dataset Fruits-360](https://github.com/SampMark/Deep-Learning/blob/main/Fruit_Classification_Using_Transfer_Learning_v1.ipynb)
  - [**_Transfer Learning_ no diagnóstico de malária**, usando o modelo VGG16 pré-treinado em ImageNet e o dataset de imagens de lâminas de células sanguíneas](https://github.com/SampMark/Deep-Learning/blob/main/transfer_learning_with_malaria_dataset_consolidated.ipynb)
  - [**_Transfer Learning_ para classificação de Resíduos Sólidos**, usando o modelo VGG16 e o dataset _Waste Classification_](https://github.com/SampMark/Deep-Learning/blob/main/classify_solid_waste_using_transfer_learning_consolidated.ipynb)
  - [**Redes Neural Convolucional (CNN) usando o dataset do MNIST do TensorFlow**: para reconhecimento de dígitos manuscritos](https://github.com/SampMark/Deep-Learning/blob/main/Convolutional_Neural_Networks_with_MNIST.ipynb)

---

### **3️⃣ Transformers no Keras**
- Considerada um "divisor de águas" em _deep learning_, especialmente no Processamento de Linguagem Natural (PLN), os **transformers** se tornaram a espinha dorsal de modelos de ponta, tais como o BERT e o GPT. Sua aplicação se expandiu para além do PLN, alcançando visão computacional e análise de séries temporais, conforme artigo seminal "_Attention is All You Need_" de Vaswani Ashish et al.
- 🔄 **Conteúdos explorados**: 
  - Construção e treinamento de transformadores para dados sequenciais.
  - Geração de texto e previsão de séries temporais com TensorFlow.
- 🧪 **Projeto**:
  - [**Arquitetura de Transformers Avançados**](https://github.com/SampMark/Deep-Learning/blob/main/Transformer_Model_Architecture.ipynb)
  - [**Transformer para geração de texto, utilizando o dataset Shakespeare**](https://github.com/SampMark/Deep-Learning/blob/main/Transformers_for_Text_Generation_consolided.ipynb)

---

### **4️⃣ Aprendizado Não Supervisionado e Modelos Generativos**
- 🤖 **Conteúdos explorados**: 
  - Desenvolvimento de modelos de autoencoders, de difusão e Generative Adversarial Networks (GAN).
- 🧪 **Projetos**:
  - [**Modelagem Autoencoder usando Keras e o dataset MNIST**, do básico até variações aplicáveis](https://github.com/SampMark/Deep-Learning/blob/main/Autoencoder_Model_using_Keras_and_MNIST_dataset_consolidated.ipynb)
  - [**Denoising Autoencoder Convolucional** usando Keras e MNIST, fundamento para Modelos Probabilisticos de Difusão](https://github.com/SampMark/Deep-Learning/blob/main/Denoising_Autoencoders_Convolucionais_consolidated.ipynb)
  - Implementação de modelo de difusão.
  - Implementação de GANs.

---

### **5️⃣ Técnicas Avançadas no Keras**
- ⚙️ **Conteúdos explorados**: 
  - Criação de loops de treinamento personalizados.
  - Ajuste de hiperparâmetros e otimização de modelos.
- 🧪 **Projetos**:
- [**Implementação de loops de treinamento com KerasTuner e ajuste de hiperparâmetros**](https://github.com/SampMark/Deep-Learning/blob/main/Training_Loops_with_KerasTuner_Consolided.ipynb).
- [**Ajuste de Hiperparâmetros com a implementação de loops de treinamento avançados, usando o KerasTuner e o HyperbandOracle**](https://github.com/SampMark/Deep-Learning/blob/main/Hyperparameter_Tuning_using_Advanced_Training_Loops_with_KerasTuner_and_Hyperband.ipynb)

---

### **6️⃣ Aprendizado por Reforço**
- 🕹️ **Conteúdos explorados**: 
  - Fundamentos de aprendizado por reforço e Q-Learning.
  - Desenvolvimento de redes Q profundas (DQNs).
- 🧪 **Projetos**:
- [**Deep Q-Network (DQN) para CartPole-v1**, usando Keras e Gymnasium](https://github.com/SampMark/Deep-Learning/blob/main/Deep_Q_Network_DQN_using_Keras_and_OpenAI_Gymnasium_in_CartPole_v1.ipynb)

---

## 🛠️ Ferramentas Utilizadas
- **Linguagens e Bibliotecas**:
  - 🐍 Python
  - 🧠 TensorFlow e Keras
- **Ambientes de Desenvolvimento**:
  - ☁️ Google Colab
  - 📝 Jupyter Notebook

---

 <img src="https://github.com/user-attachments/assets/ce04e8a9-7a47-44b7-a13e-a132f8531af4" alt="edX_20Advanced_20Deep_20Learning_20Specialist" width="180" style="border: none;">

|**Advanced Deep Learning Specialist**| 
|---|
| The badge earner can create custom layers and models in Keras, seamlessly integrate Keras with TensorFlow 2.x, and develop advanced convolutional neural networks (CNNs). They can also build Transformer models for sequential data and time series prediction. Additionally, they demonstrate expertise in key concepts of unsupervised learning, Deep Q-networks (DQNs), and reinforcement learning, applying these advanced techniques to solve real-world challenges with deep learning frameworks.|
| O titular deste badge é capaz de criar camadas e modelos personalizados em Keras, integrar o Keras de forma fluida ao TensorFlow 2.x e desenvolver redes neurais convolucionais (CNNs) avançadas. Também é capaz de construir modelos Transformer para dados sequenciais e previsão de séries temporais. Adicionalmente, demonstra expertise em conceitos-chave de aprendizado não supervisionado, Deep Q-networks (DQNs) e aprendizado por reforço, aplicando estas técnicas avançadas para solucionar desafios do mundo real com frameworks de aprendizado profundo.|

---


## 🤝 Contribuições
Fique à vontade para feedbacks, sugestões de melhorias e novas ideias! 
