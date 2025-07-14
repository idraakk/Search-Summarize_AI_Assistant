# 🔍 Search & Summarize AI Assistant

An intelligent web research assistant that automates the process of searching the internet and summarizing results using large language models. Combines the power of **DuckDuckGo Search** and **OpenAI GPT models** via **LangChain** to deliver concise, relevant insights from the web in seconds.

---

## 🚀 Features

- 🌐 **Real-time Web Search** using DuckDuckGo
- 🧠 **AI-Powered Summarization** using OpenAI's GPT
- 🧹 Intelligent **Text Parsing & Cleaning** with NLP
- 🪄 **Prompt Templates** with LangChain for flexible summarization
- 🧪 Simple, modular code for easy experimentation

---

## 📌 Use Cases

- Quickly researching new or trending topics  
- Summarizing recent news or articles  
- Extracting key insights from multiple web sources  
- Academic and technical topic exploration  
- Automating content curation

---

## 🛠️ Tech Stack

- **Python 3.10+**
- [LangChain](https://www.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [DuckDuckGo Search](https://pypi.org/project/duckduckgo-search/)
- [NLTK](https://www.nltk.org/)
- `dotenv` for secure API key management

---

## 🧑‍💻 How It Works

1. **User Input**: Enter a topic or question.
2. **DuckDuckGo Search**: Fetches real-time search results.
3. **Parsing Engine**: Cleans and extracts relevant content using regex and NLP.
4. **Summarization Pipeline**: Uses GPT (via LangChain) to generate a concise summary.
5. **Output**: Final summarized insight displayed to the user.

---

## 📂 Project Structure

```
search_the_internet_and_summarize.ipynb   # Main notebook
.env                                      # Environment variables (API keys)
requirements.txt                          # Dependencies
README.md                                 # Project documentation
```

---

## 🧪 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/search-summarize-ai.git
   cd search-summarize-ai
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**
   Create a `.env` file in the root directory:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

5. **Run the Notebook**
   Open `search_the_internet_and_summarize.ipynb` in Jupyter and execute step-by-step.

---

## ✅ Example Output

**Input:**  
```
"What are the latest advancements in quantum computing?"
```

**Output Summary:**  
- Companies like IBM and Google have made progress in error correction and qubit scaling.  
- New hardware and hybrid quantum-classical approaches are being explored.  
- Research is focusing on practical applications in materials science and cryptography.

---

## 📌 To-Do & Future Enhancements

- [ ] Web scraping of full article content for deeper summaries  
- [ ] Support for other search engines (Google, Bing)  
- [ ] CLI and web app interface  
- [ ] Caching and result ranking  
- [ ] PDF/CSV export of summaries  

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [LangChain](https://www.langchain.com/)
- [OpenAI](https://platform.openai.com/)
- [DuckDuckGo](https://duckduckgo.com/)
- [NLTK](https://www.nltk.org/)

---

## 💡 Author

**Idraak Mohd Khan**  
Competitive programmer & AI enthusiast  
[LinkedIn](https://www.linkedin.com/in/idraakmohdkhan) • [GitHub](https://github.com/idraakk)

---

⭐ If you found this project useful, feel free to star the repo and share it with others!
