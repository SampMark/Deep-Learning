# Deep Learning com TensorFlow e Keras

**Bem-vindo** ao meu repositório sobre **Deep Learning com TensorFlow e Keras**!  
Aqui você encontrará conceitos básicos e avançados de aprendizado profundo, utilizando as ferramentas TensorFlow e Keras.

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
  - [**_Transfer Learning_** no diagnóstico de malária, utilização de modelo pré‑treinado do ImageNet, com imagens de lâminas de células sanguíneas](https://github.com/SampMark/Deep-Learning/blob/main/transfer_learning_with_malaria_dataset_consolidated.ipynb)
  - [**Redes Neural Convolucional (CNN) usando o dataset do MNIST do TensorFlow**: para reconhecimento de dígitos manuscritos](https://github.com/SampMark/Deep-Learning/blob/main/Convolutional_Neural_Networks_with_MNIST.ipynb)

---

### **3️⃣ Transformers no Keras**
- Considerada um "divisor de águas" em _deep learning_, especialmente no Processamento de Linguagem Natural (PLN), os **transformers** se tornaram a espinha dorsal de modelos de ponta, tais como o BERT e o GPT. Sua aplicação se expandiu para além do PLN, alcançando visão computacional e análise de séries temporais, conforme artigo seminal "_Attention is All You Need_" de Vaswani Ashish et al.
- 🔄 **Conteúdos explorados**: 
  - Construção e treinamento de transformadores para dados sequenciais.
  - Geração de texto e previsão de séries temporais com TensorFlow.
- 🧪 **Projeto**:
  - [**Arquitetura de Transformers Avançados**](https://github.com/SampMark/Deep-Learning/blob/main/Transformer_Model_Architecture.ipynb)

---

### **4️⃣ Aprendizado Não Supervisionado e Modelos Generativos** (Em Construção 🚧🏗️👷)
- 🤖 **Conteúdos explorados**: 
  - Desenvolvimento de autoencoders, modelos de difusão e GANs.
- 🧪 **Projeto**:
  - Implementação de autoencoders e GANs.

---

### **5️⃣ Técnicas Avançadas no Keras** (Em Construção 🚧🏗️👷)
- ⚙️ **Conteúdos explorados**: 
  - Criação de loops de treinamento personalizados.
  - Ajuste de hiperparâmetros e otimização de modelos.
- 🧪 **Projeto**: Implementação de loops de treinamento e ajuste de hiperparâmetros.

---

### **6️⃣ Aprendizado por Reforço** (Em Construção 🚧🏗️👷)
- 🕹️ **Conteúdos explorados**: 
  - Fundamentos de aprendizado por reforço e Q-Learning.
  - Desenvolvimento de redes Q profundas (DQNs).
- 🧪 **Projeto**: Implementação de Q-Learning e DQNs.

---

## 🛠️ Ferramentas Utilizadas
- **Linguagens e Bibliotecas**:
  - 🐍 Python
  - 🧠 TensorFlow e Keras
- **Ambientes de Desenvolvimento**:
  - ☁️ Google Colab
  - 📝 Jupyter Notebook

---

## 🤝 Contribuições
Fique à vontade para feedbacks, sugestões de melhorias e novas ideias! 
