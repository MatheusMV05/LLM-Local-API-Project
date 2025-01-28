# LLM Local com LLaMA 2 e FastAPI

Este projeto é uma aplicação web desenvolvida com FastAPI que utiliza um modelo de linguagem LLaMA 2 para gerar resumos de textos fornecidos pelo usuário. Os resumos gerados são salvos como arquivos Word e podem ser baixados diretamente pela interface web.

## Recursos Principais

- **Interface Web**: Uma página inicial simples para enviar textos e visualizar os resumos gerados.
- **Resumos Baseados em LLaMA 2**: Uso de um modelo LLaMA para resumir textos.
- **Arquivos Word**: Os resumos gerados são salvos em arquivos `.docx` com nomes amigáveis.
- **Download de Arquivos**: Os arquivos podem ser baixados diretamente pela interface web.

---

## Requisitos

Antes de executar a aplicação, certifique-se de ter os seguintes requisitos instalados:

- **Python 3.8+**
- **FastAPI**
- **Jinja2**
- **Python-docx**
- **Ollama** (para rodar o modelo LLaMA)
- **Subprocesso** habilitado no ambiente

---

## Instalação

1. Clone este repositório:
```
git clone https://github.com/MatheusMV05/LLM-Local-API-Project.git
```
2. Crie um ambiente virtual:
```
python -m venv env
source env/bin/activate  # No Windows: env\Scripts\activate
```
3. Instale as dependências:
```
pip install -r requirements.txt
```
## Como usar

1. Inicie o servidor FastAPI:
```
uvicorn main:app --reload
```
2. Acesse a aplicação no navegador em:
```
http://127.0.0.1:8000
```
3. Insira o texto que deseja resumir no campo apropriado e clique em Resumir.

4. O resumo será exibido na página e poderá ser baixado como um arquivo Word.

Estrutura do Código:
    /summarize/: Endpoint para resumir o texto e gerar um arquivo Word.
    /download/{file_name}: Endpoint para download do arquivo gerado.
    run_llama: Função que interage com o modelo LLaMA via Ollama para gerar o resumo.
    save_to_word: Salva o resumo em um arquivo Word com um nome amigável baseado no conteúdo.
    extract_keyword: Extrai a palavra-chave mais relevante do resumo.
    generate_friendly_title: Gera um título amigável para o arquivo Word.
   


   
   

