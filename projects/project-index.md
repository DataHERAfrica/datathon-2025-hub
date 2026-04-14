# 📊 DataHER Datathon 2025 – Project Index

This page contains all project submissions.

---

## 🧠 Projects

### 🔹 HealthPaddie // Team name- Data Girls
- Repo: https://github.com/DataHERAfrica/datathon-2025-HealthPaddie
- Track: Healthcare
- Summary: HealthPaddie is a multilingual AI powered health assistant created to provide trusted, accessible, and easy to understand health information to individuals, especially those living in underserved or rural communities. The solution was developed during the DataHER Africa Hackathon 2025, where The team set out to solve the challenge of misinformation and poor access to verified health guidance across Nigeria and other African regions. Through a combination of Retrieval Augmented Generation, local language support, and a simple conversational interface, HealthPaddie ensures that people can receive reliable health knowledge in a format that is friendly and accessible.

The team began by identifying the core problem. Many people depend on unverified sources or hearsay for health information because of barriers such as limited literacy, language diversity, and difficulty accessing medical professionals. To make sure our system provides accurate information, we based our knowledge store on verified documents from the World Health Organization, the Nigerian Centre for Disease Control, UNICEF, and other credible health institutions. These documents were processed into numerical embeddings using a lightweight sentence transformer model and stored inside a FAISS vector database that allows fast semantic retrieval.

The team then adopted a Retrieval Augmented Generation pipeline to reduce the risk of model hallucinations. When a user enters a question, the system searches the vector database for the most relevant health facts, inserts them into a structured prompt template, and sends this context to a Groq powered LLaMA 3.1 model to generate a response. Because all answers are tied to real health documents, HealthPaddie remains factual, grounded, and safe.

Accessibility was a major part of their approach. HealthPaddie supports four Nigerian languages: English, Hausa, Yoruba, and Igbo. This allows users to interact with the assistant in a language that feels natural and familiar. The prompt template includes specific instructions for each language to ensure clear, culturally appropriate explanations. For users with limited reading ability or visual challenges, we added optional text to speech output so that responses can be read aloud. This significantly expands the reach of the tool.

The team built the interface using Streamlit to provide a friendly chat styled experience. Users can select their preferred language, type their questions, view previous messages, and optionally listen to audio answers. They also included simple chat history storage using a lightweight JSON based structure to support future improvements.

Throughout development, The team followed safe and responsible AI practices. HealthPaddie does not provide medical diagnoses. It warns users when their symptoms may indicate a serious condition and encourages them to seek professional care. The system prompt enforces these rules to ensure user safety remains the top priority.

In summary, HealthPaddie demonstrates how AI can be applied responsibly to address real public health challenges. By combining trustworthy data, multilingual support, and a clean user interface, the solution empowers people with clear and reliable health information wherever they are.

---

### 🔹 Project Name 2
- Repo: (link)
- Track: Finance
- Summary: Short description
