# Book Master

## Description

**Bookmaster: Revolutionizing Book Reading with AI**

Bookmaster is an advanced AI-powered application designed to transform the way we read, interact with, and understand books in PDF format. Leveraging cutting-edge technology, Bookmaster allows users to upload their PDF books and receive instant, intelligent answers to any questions they may have about the contents. Whether you're studying for an exam, conducting research, or simply exploring a new topic, Bookmaster makes reading more efficient and engaging by turning passive reading into an interactive learning experience.

**Key Technologies Behind Bookmaster**

At the heart of Bookmaster is a combination of powerful tools and technologies that work seamlessly to deliver a high-quality experience:

1. **Google's Gemini Pro Language Model (LLM)**:
   Bookmaster uses Google's Gemini Pro, one of the most advanced Large Language Models available today. This LLM is capable of understanding the nuances and complexities of human language, allowing Bookmaster to read and comprehend entire books. It can accurately interpret questions posed by the user and provide relevant answers by analyzing the text of the uploaded PDF. The model ensures that responses are not only correct but also insightful and contextually appropriate.

2. **Generative AI Embeddings**:
   To further enhance its understanding capabilities, Bookmaster integrates Generative AI embeddings, which allow the system to capture the essence and meaning of the text within the book. These embeddings represent the text in a way that can be processed by the AI to quickly locate relevant sections, themes, and concepts. This ensures that the system can efficiently navigate through the book and extract the most relevant information, even when faced with complex or abstract queries.

3. **FAISS Vector Database**:
   FAISS (Facebook AI Similarity Search) Vector Database is employed to store and search through the book's content. When a user asks a question, Bookmaster uses FAISS to find relevant passages from the book by comparing the user's query with the vectors generated from the text. This allows for fast and accurate retrieval of information, ensuring that users get the answers they need in real time. FAISS is especially useful for managing large volumes of data, making it an ideal tool for searching through extensive books or collections of texts.

4. **LangChain Framework**:
   The LangChain framework is a vital component of Bookmaster's architecture, enabling the integration and orchestration of multiple language models and databases. LangChain facilitates the seamless flow of information between the various models and the vector database, ensuring that the AI can efficiently answer complex, multi-step questions. This framework also supports chaining queries and responses together, allowing Bookmaster to provide nuanced, in-depth answers by breaking down larger questions into manageable parts. LangChain’s modularity enhances the app’s flexibility, allowing for easy customization and scaling as new features or models are added.

5. **Streamlit-Based User Interface**:
   One of the standout features of Bookmaster is its intuitive and user-friendly interface, built using Streamlit. Streamlit is a popular framework for creating custom data-driven web apps, and in Bookmaster, it provides an interactive, seamless experience. Users can easily upload their PDFs, type in questions, and receive answers in a clean and visually appealing format. The simplicity of the interface makes Bookmaster accessible to users of all skill levels, from tech enthusiasts to casual readers.

**Use Cases and Benefits**

- **Academic Research**: For students and researchers, Bookmaster is a game-changer. Instead of spending hours manually searching through textbooks and academic papers, users can ask specific questions and receive detailed responses, allowing for faster and more efficient research.
  
- **Exam Preparation**: Bookmaster is an invaluable tool for exam preparation. By uploading textbooks and lecture notes, students can ask the app to explain concepts, summarize sections, or clarify any doubts they may have, all in a matter of seconds.
  
- **General Reading**: Casual readers can use Bookmaster to deepen their understanding of any topic, clarify complex ideas, or simply explore interesting points from the book without needing to comb through pages.


## Getting Started

### Dependencies

* Windows 11
* [Gemini API](https://ai.google.dev)
* Python 3.12 or above
* [Requirements](https://github.com/GlashOfficial/bookmaster/blob/main/requirements.txt)
* Compiler


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
