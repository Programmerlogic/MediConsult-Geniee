# Title:MediConsult-Geniee🧞‍♂️
## Description

Functionality:

📴 Offline Mode: Works entirely offline, ensuring accessibility even in areas with limited or no internet connectivity.<br />
💊 Medical Assistance: Offers medical advice, consultations, and information on various health-related topics.<br />
🩺 Symptom Checker: Allows users to input their symptoms and receive preliminary diagnoses or recommendations for further action.<br />
🚑 First Aid Tips: Provides basic first aid tips for common injuries or medical emergencies.<br />
💊 Medication Information: Offers details about medications, including usage instructions, side effects, and precautions.<br />
🏥 Health Recommendations: Gives personalized recommendations for maintaining or improving health based on user-provided information such as age, gender, and medical history.<br />
📚 Health Education: Educates users about various medical conditions, treatments, and preventive measures.<br />

User Interface:<br />
💬 Chat Interface: Utilizes a chat-based interface for natural interaction with users, simulating a conversation with a healthcare professional.<br />
🖥️ Simple and Intuitive: Features a user-friendly interface with clear prompts and instructions for easy navigation.<br />
🎤 Voice Recognition: Supports voice input for hands-free interaction, enabling users to speak their queries or symptoms.<br />

Privacy and Security:<br />
🔒 Data Protection: Ensures the privacy and confidentiality of user data, especially in handling sensitive medical information.<br />
🔐 Local Processing: Processes user queries and data locally on the device, minimizing the risk of data breaches or unauthorized access.<br />

Platform:<br />
📱 Cross-Platform Compatibility: Compatible with various devices and operating systems, including smartphones, tablets, and desktop computers.<br />
📥 Installation: Available as a standalone application for download and installation on users' devices.<br />

Updates and Maintenance:<br />
🔄 Regular Updates: Receives periodic updates to improve functionality, accuracy, and performance based on user feedback and advancements in medical knowledge.<br />
🛠️ Maintenance: Offers maintenance and support services to address any technical issues or concerns encountered by users.<br />

Target Audience:<br />
👨‍👩‍👧‍👦 General Population: Designed to cater to individuals of all ages seeking medical advice, information, or assistance.<br />
🏞️ Remote Areas: Particularly beneficial for users residing in remote or underserved areas with limited access to healthcare facilities or professionals.<br />

Future Scope::-<br />
Personalized Healthcare Assistance:<br />
📈 Integration with Wearable Devices: The chatbot could evolve to provide more personalized healthcare assistance by integrating with wearable devices and collecting real-time health data from users. This data could be analyzed to offer tailored advice and recommendations, such as suggesting lifestyle changes, tracking medication adherence, or alerting users to potential health risks based on their individual health profiles.<br />

Advanced Diagnosis and Treatment Suggestions:<br />
💡 Machine Learning and NLP Advancements: With advancements in natural language processing and machine learning, the chatbot could become more proficient at diagnosing medical conditions and offering treatment suggestions. By continuously learning from interactions with users and staying updated with the latest medical research, the chatbot could provide increasingly accurate assessments and recommendations, potentially even assisting healthcare providers in decision-making processes.<br />

Expansion into Telemedicine Services:<br />
📱 Telemedicine Integration: As telemedicine continues to grow in popularity, the chatbot could expand its capabilities to offer virtual consultations with healthcare professionals. Users could schedule appointments, discuss their symptoms, receive preliminary assessments, and even obtain prescriptions or referrals, all through the chatbot interface. Integrating with telemedicine platforms could streamline the process of accessing healthcare services and provide convenient support to users, especially in regions with limited access to traditional healthcare facilities.<br />

## Tech Stack 
Sure, here's a brief description of each technology along with an emoji:

1. Lamma Model 🧠:<br />
   - The Lamma Model is a natural language processing (NLP) model designed for various text-based tasks, including text generation, classification, and sentiment analysis. It utilizes advanced algorithms to understand and process human language efficiently.<br />

2. LLM (Large Language Model) 🤖:<br />
   - LLM, or Large Language Model, refers to a category of NLP models, like OpenAI's GPT series, that are trained on vast amounts of text data to understand and generate human-like text. These models excel at tasks such as text completion, question answering, and language translation.<br />

3. Langchain 🔗:<br />
   - Langchain is a technology that enables the secure and decentralized storage and processing of language data. It utilizes blockchain technology to ensure data integrity, immutability, and transparency in linguistic applications.<br />

4. Hugging Face Embeddings 🤗:<br />
   - Hugging Face Embeddings are representations of words or phrases in a high-dimensional space generated using models developed by Hugging Face, a leading NLP research organization. These embeddings capture semantic relationships between words and are used in various NLP tasks such as similarity analysis and language understanding.<br />

5. Flask 🌐:<br />
   - Flask is a lightweight web framework for Python that allows developers to build web applications quickly and efficiently. It provides tools and libraries for routing requests, handling HTTP responses, and creating RESTful APIs, making it popular for building web-based NLP applications and services.<br />

## Installation steps
- Step 1: Install python<br /> 
- Step 2: Download the lamma model from :- https://www.kaggle.com/datasets/rodrigostallsikora/llama-2-7b-chat-ggmlv3-q8-0-bin<br />
          -Keep this model in the downloaded folder.<br />
- Step 3: Run requirements.txt file<br />
- Step 4: Download the vectorestoresdb i.e(The Faiss Vector Database) and keep the vectorstores folder in this folder itself<br />
          -https://drive.google.com/drive/folders/1kWt3GVqUvkxaTK4OthGF4ON9XfRRlsot<br />
It arrangement somehow looks like this:-<br />
![Screenshot (13)](https://github.com/Programmerlogic/MediConsult-Geniee/assets/90715479/5a60d595-6a88-4b21-ae42-99a204f21822)</br>
- Step 5: Then execute python app.py in cmd<br />

## Libraries & Dependencies
### Libraries
1. Flask 🌐:<br />
   - Flask is a micro web framework for Python used for building web applications.<br />
2. PromptTemplate 📝:<br />
   - PromptTemplate is a part of Langchain used for creating custom prompt templates for natural language processing tasks.<br />
3. Hugging Face Embeddings 🤗:<br />
   - Hugging Face Embeddings are used for generating word embeddings and language representations using models provided by Hugging Face.<br />
4. FAISS 📊:<br />
   - FAISS is a library used for efficient similarity search and clustering of dense vectors, often used in natural language processing tasks.<br />
   - `sentence-transformers` (Hugging Face model) 🤖<br />
5. SpeechRecognition 🗣️:<br />
   - SpeechRecognition is a library used for speech recognition in Python, allowing the chatbot to understand voice input from users.<br />
6. Langchain (Custom Library for NLP Tasks) 💬<br />
Langchain Modules:
- `text_splitter`: RecursiveCharacterTextSplitter 📝<br />
- `document_loaders`: PyPDFLoader, DirectoryLoader 📄<br />
- `embeddings`: HuggingFaceEmbeddings 🤗<br />
- `vectorstores`: FAISS 🔍<br />

### Dependencies
- Windows 10 💻<br />
- Python 🐍<br />
- RAM 8GB 🐏<br />
- Intel i5 Processor ⚙️<br />

