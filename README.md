Description of The Chatbot :

In response to MPEDA's Innovation Challenge, our team successfully developed a Seafood Enquiry Chatbot using Langchain. We scraped relevant data from government websites, applying NLTK, re and RecursiveTextSplitter for meticulous data cleaning and data preprocessing. Utilizing SentenceTransformerEmbeddings and Chromadb, we established an effective vector database, enabling seamless storage and retrieval of vector embeddings for diverse operations, mainly for similarity search. In this chatbot, GPT-3.5-turbo streamlined question answering, extending its functionality to question answering from CSV files also. For image classification, we implemented EfficientNet80, a pre-trained CNN architecture, coupled with BARD API for detailed image descriptions. Integration via Flask provided a unified interface, complemented by REST APIs for real-time updates on recent seafood and business news. Our implementation prioritized network security, encompassing password verification, removing explicit content and prompt leaking, secure user authentication through login and signup features and providing follow-up emails using summary of chats using smtplib library.

Instructions to use the Chatbot:

git clone https://github.com/SRINJOY59/Seafood_Chatbot.git
pip install bardapi
go to bard-> console-> application -> cookies-> bard link -> _Secure - 1PSID api key 4)pip install langchain
pip install openai
pip install pyPDF2
pip install faiss-cpu
pip install openai langchain sentence_transformers
pip install chromadb
pip install cohere tiktoken
pip install llmx==0.0.15a0
pip install unstructured
pip install kaleido

pip install tiktoken If tensorflow and opencv not installed in system pip install tensorflow pip install cv2 pip install opencv-python
To access BARD API KEY: os.environ['_BARD_API_KEY'] = 'your_api_key' Process to generate this API KEY: Bard website -> console -> application -> cookies -> https://bard.google.com ->_Secure - 1PSID API key

Running the application in terminal: python app.py

Work Flow 1)Signup as new user 2)MPEDA Specific Query button on Sidebar 3)News cards showing latest news 4)Enter Your required query 5)Upload your Required Image to have details 6)Upload your required CSV file to question 7)Use Translate dropdown 8)Click the Required Buttons as per your options
