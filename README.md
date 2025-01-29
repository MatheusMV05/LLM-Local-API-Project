# LLM Local com LLaMA 2 e FastAPI

Bem-vindo ao **LLM Local com LLaMA 2 e FastAPI**, uma aplicação web moderna e eficiente para gerar resumos automáticos de textos usando inteligência artificial. Com uma interface intuitiva e processamento rápido, você pode transformar qualquer texto em um resumo conciso e baixar o resultado como um arquivo Word.

## 🚀 Recursos Principais

- 🌐 **Interface Web Intuitiva**: Envie textos facilmente e visualize os resumos gerados.
- 🧠 **Resumos Inteligentes com LLaMA 2**: Utiliza o poderoso modelo LLaMA 2 para criar resumos precisos e eficientes.
- 📄 **Exportação para Word**: Salve seus resumos em arquivos `.docx` para fácil compartilhamento e edição.
- 📥 **Download Direto**: Baixe os resumos rapidamente pela interface web.

---

## 📌 Requisitos

Antes de executar a aplicação, certifique-se de ter os seguintes itens instalados:

- **Python 3.8+**
- **FastAPI**
- **Jinja2**
- **Python-docx**
- **Ollama** (para rodar o modelo LLaMA 2)

---
Caso não tenha instalado baixe e instale o Ollama a partir do link oficial:
https://ollama.com/download

## ⚙️ Instalação

1️⃣ Clone este repositório:
```sh
 git clone https://github.com/MatheusMV05/LLM-Local-API-Project.git
```
2️⃣ Crie e ative um ambiente virtual:
```sh
python -m venv env
source env/bin/activate  # No Windows: env\Scripts\activate
```
3️⃣ Instale as dependências:
```sh
pip install -r requirements.txt
```
---

## ▶️ Como Usar

1️⃣ Inicie o servidor FastAPI:
```sh
uvicorn main:app --reload
```
2️⃣ Acesse a aplicação no navegador:
```sh
http://127.0.0.1:8000
```
3️⃣ Insira o texto no campo apropriado e clique em **Resumir**.

4️⃣ Visualize o resumo gerado e baixe-o como um arquivo Word.

💡 **Dica:** Experimente textos de diferentes tamanhos e veja como o LLaMA 2 se adapta para criar resumos otimizados!

---

🚀 **Experimente agora e aproveite a praticidade dos resumos automáticos com LLaMA 2!**

