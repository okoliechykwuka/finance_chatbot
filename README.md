# FinAPP
**Project Name:** FinAPP

**Project Description:**
The Chatbot Document and Data Retrieval System is a powerful tool designed to simplify and enhance information retrieval from a wide range of company documents and data sources. This system allows users, typically companies, to effortlessly upload their documents, including PDFs, TXT, and DOCX files, as well as structured data in Excel and CSV formats. Furthermore, it facilitates seamless integration with databases, such as SQL Server and PostgreSQL, to expand its knowledge base. 

**Value of the Project:**
Thi project's true value lies in its ability to transform the laborious task of reading through large volumes of company documents into a straightforward interaction with a context-aware chatbot. The system can not only answer questions but also summarize, rephrase, and present responses in a clear and understandable manner. By harnessing the power of OpenAI's GPT-3.5 language model, this chatbot system ensures that answers are rooted in the provided context, minimizing the risk of generating incorrect information. In essence, it streamlines the process of contextual chat and information retrieval.

**Reason for the Project:**
The FinAPP was conceived to address the specific need for a context-aware chatbot capable of interacting with multiple knowledge sources, including documents, data, and databases. By focusing on the context, this system aims to prevent inaccuracies and hallucinations that can occur with unbounded language models. It serves as an essential tool for companies seeking a reliable means to access and extract valuable information from their own knowledge repositories.

**Technology Behind the Project:**
- **GPT-3.5 (OpenAI Large Language Model):** This state-of-the-art language model is central to the system's ability to provide accurate and contextually relevant responses.
- **LangChain Python Library:** LangChain simplifies the chaining of large language models, making it easier to handle complex interactions.
- **Vector Stores (Chroma):** These serve as a database of vectorized words, enhancing the system's capability to understand and process text.
- **Streamlit:** This user-friendly web application framework streamlines the creation of the chatbot interface, making it highly accessible for users without extensive technical expertise.

**Front-End Tool:**
Streamlit has been chosen as the front-end tool due to its simplicity and efficiency in creating a user-friendly chatbot interface. It facilitates quick deployment and a smooth user experience.

**Functions:**
- Provides a chat interface for user interaction.
- Accepts various document formats, including PDF, TXT, and DOCX.
- Handles structured data in Excel and CSV files.
- Connects seamlessly to databases.
- Extracts relevant information from documents and data sources to respond to user queries.
- Ensures responses are contextually accurate by not answering questions when the answer isn't in the provided context.

This chatbot document and data retrieval System simplifies and enhances the process of summarizing and retrieving information from company-specific knowledge sources while maintaining the context of the chat, ensuring accuracy and reliability in knowledge extraction.

![Architecture_Diagram] (fin_app.png, "Diagram").


run in cmd
$pip install requirments.txt
$streamlit run app.py
 