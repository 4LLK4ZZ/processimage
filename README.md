# 🖼️ Processamento de Imagens com Pillow

Este repositório reúne estudos e exemplos práticos de **Processamento de Imagens em Python** utilizando a biblioteca **Pillow (PIL)**.

O objetivo do projeto é demonstrar técnicas fundamentais de manipulação de imagens, incluindo leitura, edição, transformação, aplicação de filtros e geração de novas imagens de forma programática.

---

## 📂 Estrutura do Repositório

| Diretório / Arquivo        | Descrição                                                                          |
| -------------------------- | ---------------------------------------------------------------------------------- |
| 📂 `img/`                  | Diretório contendo imagens utilizadas nos exemplos e testes de processamento.      |
| 📓 `processa_imagem.ipynb` | Notebook com exemplos de manipulação e transformação de imagens utilizando Pillow. |
| `.gitignore`               | Configuração para ignorar arquivos temporários, caches e ambientes virtuais.       |

---

## 🛠️ Tecnologias Utilizadas

### Python

Linguagem principal utilizada para o desenvolvimento dos exemplos.

### Pillow (PIL)

Biblioteca responsável pelas operações de processamento de imagens, como:

* Leitura e salvamento de arquivos;
* Redimensionamento;
* Recorte (*crop*);
* Rotação;
* Conversão de formatos;
* Aplicação de filtros;
* Ajuste de brilho e contraste;
* Manipulação de cores.

### Jupyter Notebook

Ambiente interativo utilizado para experimentação e visualização dos resultados.

---

## 🚀 Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/processamento-imagens-pillow.git
cd processamento-imagens-pillow
```

### 2. Crie um ambiente virtual

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**Linux/macOS**

```bash
python -m venv .venv
source .venv/bin/activate
```

### 3. Instale as dependências

```bash
pip install pillow notebook matplotlib
```

### 4. Inicie o Jupyter Notebook

```bash
jupyter notebook
```

### 5. Abra o notebook

```text
processa_imagem.ipynb
```

---

## 📸 Funcionalidades Demonstradas

### 🔍 Leitura de Imagens

* Abertura de arquivos JPG, PNG e outros formatos suportados.

### 📏 Redimensionamento

* Alteração das dimensões das imagens mantendo ou não a proporção.

### ✂️ Recorte (Crop)

* Seleção de regiões específicas da imagem.

### 🔄 Rotação e Espelhamento

* Rotação em diferentes ângulos.
* Espelhamento horizontal e vertical.

### 🎨 Conversão de Cores

* RGB → Escala de Cinza.
* RGB → Preto e Branco.

### ✨ Aplicação de Filtros

* Blur
* Sharpen
* Edge Detection
* Contour

### 💾 Exportação

* Salvamento das imagens processadas em diferentes formatos.

---

## 📚 Conceitos Abordados

* Manipulação de pixels
* Espaços de cores
* Transformações geométricas
* Filtros digitais
* Automação de tarefas de edição de imagens

---

## 🎯 Objetivo

Este projeto foi desenvolvido com fins educacionais para explorar os recursos da biblioteca Pillow e servir como base para projetos mais avançados de visão computacional e processamento digital de imagens.

---

## 👨‍💻 Autor

Desenvolvido por **4LLK4ZZ**.
