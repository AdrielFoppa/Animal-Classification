# 🐾 Classificação de Animais com CNN

Modelo de classificação de imagens construído do zero usando redes neurais convolucionais (CNN) com TensorFlow/Keras.

## 📊 Dataset
- [**Animals-10**](https://www.kaggle.com/datasets/alessiocorrado99/animals10) (~26.000 imagens, 10 classes) 
- Classes: Borboleta, Gato, Galinha, Vaca, Cachorro, Elefante, Cavalo, Ovelha, Aranha, Esquilo

## 🏗️ Arquitetura
CNN sequencial com 4 blocos convolucionais (32 → 64 → 128 → 256 filtros), Batch Normalization, MaxPooling e Dropout, seguidos de camadas densas para classificação.

## 🔧 Técnicas utilizadas
- Data Augmentation (rotação, flip, zoom, deslocamento)
- Pipeline eficiente com `ImageDataGenerator` (sem carregar tudo na RAM)
- EarlyStopping e ReduceLROnPlateau
- Treinamento em 50 épocas

## 📈 Resultado
- **Acurácia final: 88.25%**

## Como recriar 🚀
[Instruções](iunstrucoes.md)

## 🚀 Como usar
```python
from tensorflow.keras.models import load_model
model = load_model('animal_classification.keras')
```

## 🛠️ Tecnologias
`Python` `TensorFlow` `Keras` `Matplotlib` `NumPy`
