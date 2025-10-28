# 🌐 Azure Article Translator 2025

Projeto de estudo que integra **Azure OpenAI GPT-4o-mini** e **Azure Translator** para tradução automática de documentos `.docx`, tanto via Google Colab quanto em ambiente local Windows.  
> ⚙️ Ideal para quem quer testar o poder da API do Azure OpenAI em pipelines de tradução de arquivos.

---

## 🚀 Estrutura do Projeto

azure-article-translator-2025/
├─ src/
│ ├─ test_openai.py
│ ├─ translate_docx_openai.py
│ └─ translate_docx_translator.py
├─ notebooks/
│ ├─ translate_docx_openai_colab.ipynb
│ └─ translate_docx_azure_win.ipynb
├─ assets/
│ ├─ azure_portal.png
│ ├─ colab_run.png
│ ├─ code_main.png
│ ├─ word_result.png
│ ├─ powershell_ok.png
│ ├─ result_compare.png
│ └─ final_doc.png
├─ .env.example
├─ requirements.txt
├─ .gitignore
└─ README.md
## 🧠 Tecnologias Usadas
- **Azure OpenAI GPT-4o-mini**
- **Azure Translator API**
- **Python 3.12**
- `requests`, `python-docx`, `tqdm`, `openai`, `dotenv`

---

## ⚙️ Como Rodar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/marcosgaia/azure-article-translator-2025.git
   cd azure-article-translator-2025
Instale as dependências:

bash
Copiar código
pip install -r requirements.txt
Copie o arquivo .env.example para .env e preencha com suas chaves Azure:

bash
Copiar código
AZURE_OPENAI_ENDPOINT=https://<seu-endpoint>.openai.azure.com/
AZURE_OPENAI_KEY=<sua-chave>
AZURE_OPENAI_DEPLOYMENT=gpt-4o-mini
AZURE_OPENAI_API_VERSION=2024-06-01
Execute o script principal:

bash
Copiar código
python src/translate_docx_openai.py
☁️ Passo a Passo no Azure Portal
1️⃣ Acesse portal.azure.com
2️⃣ Crie um Resource Group para o projeto
3️⃣ Procure por Azure OpenAI → Create
4️⃣ Na aba Keys and Endpoint, copie o endpoint e a key
5️⃣ Crie também um Azure Translator
6️⃣ Guarde as duas chaves no arquivo .env
7️⃣ Pronto! Agora é só rodar os scripts e traduzir .docx em lote 🎯

🖼️ Demonstração
🔹 Configuração no Azure Portal

🔹 Execução no Google Colab

🔹 Código principal do tradutor

🔹 Resultado da tradução

🔹 Projeto criado via PowerShell

🔹 Comparativo final

🔹 Documento final traduzido

🧩 Autor
Marcos Gaia
💼 Analista de Suporte Técnico | 🔒 Cibersegurança & Forense Digital
📍 Rio de Janeiro, Brasil



🧭 Licença
Este projeto é open-source sob a licença MIT.

yaml
Copiar código
