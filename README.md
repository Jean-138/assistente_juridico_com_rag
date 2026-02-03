# Assistente Jurídico com RAG

**Projeto de curso**: app web que carrega um PDF jurídico e responde dúvidas usando apenas o conteúdo do documento.  
Utiliza RAG (Retrieval-Augmented Generation) com Streamlit, LangChain, Groq e ChromaDB.

Demo online: https://assistentejuridicocomragpy-38ec7mn9lhaw2i3n9rwvqq.streamlit.app/

---

## Como rodar localmente

```bash
git clone https://github.com/Jean-138/assistente_juridico_com_rag.git
cd assistente_juridico_com_rag
pip install -r requirements.txt
streamlit run assistente_juridico_com_rag.py
