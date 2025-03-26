#  Sistema de Busca Inteligente para PDFs sobre Mercado Financeiro

## Sobre o Projeto
Este projeto tem como objetivo facilitar a análise e correlação de artigos científicos e documentos sobre o **mercado financeiro**. Através da implementação de **busca vetorial e inteligência artificial**, é possível carregar arquivos PDF, indexá-los e recuperar informações de forma eficiente.

## Objetivos
✅ Carregar arquivos PDF contendo informações relevantes sobre mercado financeiro.
✅ Implementar um **sistema de busca vetorial** para indexação e recuperação de informações.
✅ Utilizar **inteligência artificial** para responder perguntas baseadas no conteúdo dos PDFs.
✅ Desenvolver um **chat interativo** para facilitar a busca de informações contextuais.

## Tecnologias Utilizadas
- **Python** para manipulação de textos e PDFs
- **LangChain** para processamento e busca contextual
- **FAISS (Facebook AI Similarity Search)** para indexação vetorial
- **gpt-4o** para geração de respostas baseadas nos PDFs
- **Streamlit** para criação de uma interface interativa

## Estrutura do Repositório
```
├── inputs/                   # Pasta para armazenar PDFs e textos de exemplo
│   ├── exemplo.pdf           # Documento de exemplo sobre mercado financeiro
│   ├── sentencas.txt         # Frases extraídas dos PDFs para análise
│
├── app.py                    # Código principal do projeto
├── requirements.txt          # Bibliotecas necessárias para rodar o projeto
├── readme.md                 # Documentação do projeto
```

## Como Utilizar
### 1️⃣ Clone o repositório e instale as dependências
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
pip install -r requirements.txt
```

### 2️⃣ Adicione seus PDFs na pasta `inputs/`
Inclua arquivos relevantes sobre o mercado financeiro para análise.

### 3️⃣ Execute a aplicação
```bash
streamlit run app.py
```

### 4️⃣ Interaja com o Chat
Faça perguntas relacionadas ao conteúdo dos PDFs e obtenha respostas contextuais!

## Exemplos de Perguntas
- "Qual foi o impacto da taxa Selic nos investimentos em 2024?"
- "Como funciona a alocação de ativos em um portfólio diversificado?"
- "Quais são as tendências do mercado financeiro para os próximos anos?"

## Insights e Possibilidades
- Permite **agregar múltiplos artigos** e **extrair insights mais rapidamente**.
- Facilita a **correlação de conceitos** entre diferentes documentos.
- Pode ser **expandido** para outras áreas, como direito, medicina e engenharia.

## Prints do Projeto
*(Adicione aqui imagens mostrando o funcionamento do sistema!)*

## Contribuições
Se tiver sugestões ou melhorias, sinta-se à vontade para contribuir!
Abra uma issue ou faça um pull request. 🚀



