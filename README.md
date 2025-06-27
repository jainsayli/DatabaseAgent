# 🧠 GenAI-Powered Database Agent

This project is a prototype of a **natural language-to-SQL database agent** built using:
- 🧠 Azure OpenAI (ChatGPT API)
- 🗃️ SQLite
- 🔗 LangChain
- 📓 Jupyter Notebook

The agent allows users to ask questions in plain English (like *"Show all employees in the HR department"*) and receive actual SQL query results from a connected `.db` file.

---

## 🚀 Features

- Convert natural language to SQL using GPT via Azure OpenAI
- Query a local SQLite database (`.db` file)
- Built with LangChain's SQLDatabaseToolkit
- Python + Jupyter Notebook interface
- Extendable to other DBs (MySQL, PostgreSQL) and vector stores

---

## 🛠️ Technologies Used

- `langchain`
- `langchain-openai`
- `sqlite3`
- `SQLAlchemy`
- `pandas`
- `tabulate`
- `Jupyter Notebook`
- `Azure OpenAI (gpt-4 / gpt-35-turbo deployment)`

---

## 📂 Folder Structure
DatabaseAgent/
├── Scripts/
│ ├── DatabaseAgent.ipynb # Main notebook
│ ├── test.db # SQLite database file
│ ├── sample.csv # (Optional) CSV data source
├── README.md # Project documentation

1. Clone the repository:

```bash
git clone https://github.com/jainsayli1/DatabaseAgent.git
cd DatabaseAgent

2. (Optional) Create a virtual environment and activate it
3. Install required packages:
   pip install langchain langchain-openai
   pip install langchain-experimental
   pip install tabulate

💬 Example Query
agent.invoke("How many employees work in the Finance department?")

🧩 Future Enhancements
Voice input and audio responses

Web interface (using Gradio or Streamlit)

Support for multiple database types

🧑‍💻 Author
Sayli Jain
🔗 GitHub
