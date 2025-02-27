# 🖼️ Modelo de Reconhecimento de Pessoas com MobileNet

## 📖 Sobre
Este projeto utiliza a arquitetura MobileNet para realizar a classificação de imagens em duas categorias: **"NENHUM"** e **"PESSOA"**. O objetivo é identificar se uma imagem contém uma pessoa ou não, utilizando um modelo treinado e posteriormente convertido para **TensorFlow Lite** para aplicações otimizadas.

## ⚙️ Como funciona?
O modelo é treinado com imagens rotuladas e passa por um processo de aprimoramento, incluindo:
- **Pré-processamento**: Redimensionamento das imagens para **96x96 pixels** e normalização dos valores dos pixels.
- **Treinamento**: Utilização da MobileNet com camadas personalizadas para classificação binária.
- **Aprimoramento**: Ajuste fino dos pesos do modelo para melhorar a acurácia.
- **Conversão**: O modelo é convertido para **TensorFlow Lite** com quantização para rodar em dispositivos embarcados.

## 💡 Objetivo
O projeto visa criar um sistema eficiente de reconhecimento de pessoas que possa ser utilizado em dispositivos com **baixa capacidade computacional**, como sistemas de monitoramento e aplicações móveis.

## 💻 Tecnologias Utilizadas
O modelo foi desenvolvido em Python e utiliza as seguintes bibliotecas:

- **TensorFlow/Keras** – Para criação e treinamento do modelo MobileNet
- **OpenCV** – Para manipulação e pré-processamento das imagens
- **NumPy** – Para operações matemáticas e manipulação de arrays
- **Scikit-learn** – Para dividir os dados e avaliar a performance do modelo
- **Matplotlib/Seaborn** – Para visualização dos resultados e análise das métricas

