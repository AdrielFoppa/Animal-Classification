## 🚀 Como executar o projeto

Siga os passos abaixo para rodar o projeto localmente.

### 1️⃣ Clonar o repositório
```[bash]
git clone https://github.com/AdrielFoppa/Animal-Classification.git
cd Animal-Classification
```

### 2️⃣ Baixar o dataset

O dataset não está incluído no repositório devido ao tamanho.

Link:
https://www.kaggle.com/datasets/alessiocorrado99/animals10

Após baixar:
- Extraia o arquivo .zip
- Renomeie a pasta para raw-img 
- Coloque a pasta dentro do diretório do projeto

### 3️⃣ Estrutura esperada

```
Animal-Classification/
│
├── raw-img/
│   ├── cane/
│   │   ├── img1.jpg
│   │   ├── img2.jpg
│   │   └── ...
│   ├── cavallo/
│   │   ├── img1.jpg
│   │   ├── img2.jpg
│   │   └── ...
│   ├── gatto/
│   ├── mucca/
│   ├── pecora/
│   ├── elefante/
│   ├── farfalla/
│   ├── ragno/
│   └── scoiattolo/
│
├── some_tests/
│   ├── butterfly.png
│   ├── cat.png
│   ├── cow.jpg
│   ├── elephant.jpg
│   ├── horse.jpg
│   ├── sheep.webp
│   ├── spider.avif
│   └── squirrel.jpg
│
├── instructions.md
├── model_structure.ipynb
└── README.md
```

### 4️⃣ Executar o notebook

jupyter notebook

Ou abra no VS Code e execute:
model_structure.ipynb

Execute todas as células para treinar o modelo.

### ⚠️ Observações

- O treinamento pode demorar dependendo do hardware utilizado.
- Recomenda-se a utilização de GPU para melhor desempenho.
- Verifique se os caminhos do dataset estão corretamente configurados no notebook.
- Este projeto foi desenvolvido utilizando **Python 3.12**.
