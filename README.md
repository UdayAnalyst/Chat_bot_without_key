
# 🧠 PDF GPT Chatbot using LangChain + LlamaCpp

This project lets you **ask questions to a PDF document** using local LLMs like **Mistral 7B** and tools like **LangChain**, **LlamaCpp**, and **ChromaDB**.

🚀 Upload any PDF → Chunk it → Embed it → Ask questions → Get smart, contextual answers — all offline!

---

## 🔧 Features

- 📄 Load PDFs using `PyPDFLoader`
- ✂️ Split and chunk text with `RecursiveCharacterTextSplitter`
- 🧠 Use `sentence-transformers` (MiniLM) for embeddings
- 🗃️ Store vector embeddings using `ChromaDB`
- 🤖 Answer questions with local model (`Mistral-7B-OpenOrca.Q4_0.gguf`)
- 🧾 Built with LangChain & LlamaCpp on your local machine

---

## 📦 Technologies Used

- `LangChain`
- `LlamaCpp`
- `ChromaDB`
- `sentence-transformers`
- `PyPDFLoader`
- `HuggingFaceEmbeddings`
- `Jupyter Notebook`

---

## 🖥️ Demo Screenshot

> *(Add a screenshot here showing the notebook answering a question)*

---

## 🧪 How to Run This Project

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/pdf-gpt.git
cd pdf-gpt
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Download Mistral GGUF Model

Place the `mistral-7b-openorca.Q4_0.gguf` file inside the project directory.

You can find models from:  
👉 https://huggingface.co/TheBloke/Mistral-7B-OpenOrca-GGUF

### 4. Run the Notebook

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open `PDF_GPT.ipynb`, update your **PDF file path**, and start asking questions!

---

## 📁 Folder Structure

```bash
📁 pdf-gpt
 ┣ 📄 PDF_GPT.ipynb
 ┣ 📄 requirements.txt
 ┣ 📄 mistral-7b-openorca.Q4_0.gguf  ← (You must download separately)
 ┗ 📄 README.md
```

---

## 📌 To-Do (Optional Enhancements)

- [ ] Add a Streamlit or Gradio UI
- [ ] Add support for multiple PDFs
- [ ] Enable web-based demo

---

## 📢 Connect

Made with ❤️ by **Uday Pandey**  
📬 Reach me on [LinkedIn](https://linkedin.com/in/uday-pandey)
