# Semantic Spotter AI Project GenAI UpGrad IIITB
Simplifying insurance document queries with the power of Retrieval-Augmented Generation (RAG) and advanced embeddings with Llama-Index and OpenAI's GPT models.

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)](https://www.python.org/)

---

## ✨ About the Project
RAG Insurance Assistant is an innovative solution designed to simplify the process of understanding and extracting information from complex insurance documents. Traditional methods of sifting through policy documents, claim guidelines, and legal jargon can be time-consuming and frustrating for users. This project eliminates these pain points by leveraging **Retrieval-Augmented Generation (RAG)** technology powered by **LlamaIndex**.

The assistant utilizes **LlamaIndex** to efficiently retrieve relevant sections of insurance documents and combines it with the natural language generation capabilities of state-of-the-art AI models like GPT-4 or Gemini. This two-step approach ensures accurate, context-aware responses to user queries, making insurance information easily accessible.

Key Benefits:
- **Streamlined Information Access**: Forget endless searches—ask specific questions and receive precise, concise answers instantly.
- **Enhanced Contextual Understanding**: Breaks down complex legal language into user-friendly explanations.
- **Powerful Scalability**: Handles large datasets effortlessly, making it suitable for both personal and enterprise-level applications.

Whether you're a policyholder seeking clarity on coverage or an insurance agent streamlining customer service, the RAG Insurance Assistant transforms the way users interact with insurance documents.


Example Use Cases:
- "What is covered under my health insurance policy?"
- "How can I file a claim for vehicle insurance?"

---

## 🔍 Key Features
- 🌟 **Efficient Document Retrieval**: Harness the power of LlamaIndex to retrieve highly relevant sections of insurance documents quickly, ensuring precise answers tailored to user queries.
- 🤖 **Context-Aware Responses**: Combines advanced retrievers with AI language models (GPT-4 or Gemini) to generate contextually accurate, natural-language answers from dense insurance policies.
- 🔄 **Seamless Integration with Vector Stores**: Leverages ChromaDB for storing and querying embeddings, ensuring lightning-fast and scalable performance even with large datasets.
- 📄 **Document Agnostic**: Supports various document formats, including PDFs, Word files, and text files, making it versatile for processing any insurance-related material.
- 🧩 **Flexible Chunking Strategies**: Employs customizable document chunking methods, including overlapping techniques, to optimize retrieval accuracy and avoid information gaps.
- 🌐 **Cloud or Local Deployment**: Fully adaptable to your infrastructure needs—deploy locally for personal use or on the cloud for enterprise applications.
- 🔑 **Secure Access**: Ensures data privacy by handling sensitive insurance data with secure API key management and controlled access.
- 📊 **Analytics-Ready**: Optionally integrates with analytics tools to track query patterns and optimize document updates or user experience.
- 💬 **Interactive and User-Friendly**: Offers a conversational interface for asking policy-related questions, eliminating the need to read through lengthy documents.
- 🚀 **Future-Ready Architecture**: Easily extendable to support additional domains or industries beyond insurance, such as legal or healthcare documentation.

---

## 🛠️ Tech Stack
- **Language**: Python-In Jupyter Notebook
- **Frameworks/Libraries**: Transformers, ChromaDB, PDFplumber, Llama-Index, Disk Cache
- **APIs/Models**: OpenAI's GPT-4/ GPT-4o/ GPT-4o-mini or Gemini API or any other State-of-the-Art models
- **Tools used**: Jupyter Notebook

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Docker (optional, for containerized deployment)

### Installation
1. Clone the repo:
git clone https://github.com/SandeepGitGuy/Semantic_Spotter_AI_Project_GenAI_UpGrad_IIITB.git

2. Navigate to the project directory:
cd Semantic_Spotter_AI_Project_GenAI_UpGrad_IIITB

3. Install the required dependencies:
pip install -r requirements.txt

- Please note: OpenAI API keys are required for the project to function. You can obtain them from the OpenAI website and change the same in the code. We have updated the code and added more models to make it more dynamic in V2 of the project.

4. Run the main file from Jupyter environment:
"Semantic_spotter_lamaindex_Sandeep.ipynb"

---

## 📖 Documentation
No documentation will be made available for this project since this project only uses technologies that already have their own documentation. Please refer to the following links for more information:
- [ChromaDB](https://docs.trychroma.com/)
- [PDFplumber](https://pypi.org/project/pdfplumber/0.1.2/)
- [Sentence Transformes](https://www.sbert.net/docs/)
- [OpenAI](https://platform.openai.com/docs/)
- [Llama-Index](https://www.llamaindex.ai/)

---

## 🛠️ Challenges/Issues Faced with fixes

- [Issue #1](Cache layer was added in ChromaDB to prevent re-embedding of the data. This was done to avoid overloading the ChromaDB server with data and to make the retrieval process more efficient.)

- [Issue #2](Cross Encoder based Reranker was added to better select the most relevant passages from the document. This was done to improve the quality of the answers to the user queries.)

- [Issue #3](Verifying the correctness of the answers given by the model was a challenge. We used GPT-4 to verify the answers provided by the model since it is a state-of-the-art model. This was done to ensure that the answers provided by the model are accurate and relevant. We also included a human feedback system to verify the correctness of the answers provided by the model. This was done to ensure that the answers provided by the model are accurate and relevant.)

---

## 🌟 Future Improvements
- [ ] Add more selectable GPT models to the project(Gemini, Claude AI, Huggingface models etc).
- [ ] Add more features to the project.
- [ ] Add more selectable Vector Store to the project(Pinecone, Weaviate etc).

---

## 🛡️ License
Distributed under the MIT License. See `LICENSE` for more information.

---

## 💬 Contact
For any queries or feedback, feel free to reach out:

- **Email**: sandy974278@gmail.com
- **GitHub**: https://github.com/SandeepGitGuy
- **LinkedIn**: www.linkedin.com/in/sandeepgowda24a319192

---