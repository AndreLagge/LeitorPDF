# LeitorPDF
# 📄 Protótipo TCC — Leitor Inteligente de PDFs Técnicos (Português)

Este projeto implementa um sistema local para leitura, resumo e interação com documentos técnicos em PDF, voltado para uso em português, especialmente para aplicações como auditorias, manuais e normas.

## ✨ Funcionalidades

- 🧠 **Extração de texto** de arquivos PDF com estrutura preservada;
- 📚 **Resumo automático** (extrativo) dos conteúdos;
- ❓ **Sistema de Perguntas e Respostas** (QA) baseado em PLN;
- 🌐 Interface Web com **Gradio**, simples e interativa.

## 🛠️ Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/seuusuario/tcc-pdf-nlp.git
cd tcc-pdf-nlp
pip install -r requirements.txt

📁 Estrutura do Projeto
.
├── tcc_prototipo.py
├── requirements.txt
└── README.md

🧪 Modelos Utilizados
pierreguillou/bert-base-cased-squad-v1.1-portuguese: modelo de QA treinado em português.

sumy com LSA: para sumarização extrativa de textos longos.

🔐 Observações
Este protótipo é local e não envia dados para servidores externos, garantindo segurança e conformidade com diretrizes como a LGPD.

🧑‍💻 Autor
Projeto desenvolvido como parte de um TCC do curso de especialização em Data Science & Analytics.

