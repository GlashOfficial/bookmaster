# Book Master

## Description

**Bookmaster: Revolutionizing Book Reading with AI**

Bookmaster is an innovative AI tool that transforms how users read and understand books in PDF format. With Bookmaster, you can upload any PDF book and ask questions directly about its content. It uses advanced AI to provide quick and accurate answers, making reading more interactive and efficient.

<br>

Key features of Bookmaster include:

1. **Google's Gemini Pro LLM**: This powerful language model allows Bookmaster to understand complex text and respond intelligently to your questions by analyzing the content of the book.

2. **Generative AI Embeddings**: These embeddings help the AI understand the meaning of the text, ensuring that it can locate and retrieve the most relevant sections of the book based on your query.

3. **FAISS Vector Database**: This database stores the book’s text and enables fast searches for specific information, allowing for quick, relevant answers to your questions.

4. **LangChain Framework**: LangChain helps manage complex queries by connecting multiple AI tools, ensuring that Bookmaster can provide detailed, multi-step answers if needed.

5. **Streamlit UI**: The user-friendly interface built with Streamlit makes it easy to upload PDFs, ask questions, and get answers in a simple and intuitive layout.

<br>

**Use Cases and Benefits**

- **Academic Research**: For students and researchers, Bookmaster is a game-changer. Instead of spending hours manually searching through textbooks and academic papers, users can ask specific questions and receive detailed responses, allowing for faster and more efficient research.
  
- **Exam Preparation**: Bookmaster is an invaluable tool for exam preparation. By uploading textbooks and lecture notes, students can ask the app to explain concepts, summarize sections, or clarify any doubts they may have, all in a matter of seconds.
  
- **General Reading**: Casual readers can use Bookmaster to deepen their understanding of any topic, clarify complex ideas, or simply explore interesting points from the book without needing to comb through pages.

<br>

Bookmaster represents a significant leap forward in AI-powered reading assistance. By combining the power of Google's Gemini Pro LLM, Generative AI embeddings, FAISS Vector Database, LangChain Framework, and a user-friendly Streamlit interface, Bookmaster provides an innovative solution for anyone looking to get more out of their reading experience. Whether for academic, professional, or personal use, this program makes understanding books easier, faster, and more interactive than ever before.
## Getting Started

### Dependencies

* Windows 11
* [Gemini API](https://ai.google.dev)
* Python 3.12 or above
* [Requirements](https://github.com/GlashOfficial/bookmaster/blob/main/requirements.txt)


### TODO

* Clone the repository to your folder
```
git clone https://github.com/GlashOfficial/bookmaster.git
```
* Install the requirements
```
pip install -r requirements.txt
```

### Executing the program

* Paste your Gemini API in .env file
```
GOOGLE_API_KEY='your_api_key'
```
* Run the application from compiler terminal
```
streamlit run bookmaster.py
```

## Authors

Glash
[@Glash4k](https://x.com/Glash4k)

## Version History
* 1.0
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
