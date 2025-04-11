# 📧 Cold Mail Generator

Cold email generator for services companies using **GROQ**, **LangChain**, and **Streamlit**.

This tool allows users to input the URL of a company’s careers page. It then extracts job listings from that page and generates **personalized cold emails**, including relevant portfolio links sourced from a **vector database**, based on the extracted job descriptions.

---
**Imagine a scenario:**

- Nike needs a Principal Software Engineer and is spending time and resources in the hiring process, on boarding, training etc
- Atliq is Software Development company can provide a dedicated software development engineer to Nike. So, the business development executive (Mohan) from Atliq is going to reach out to Nike via a cold email.

![img.png](imgs/img.png)

## Architecture Diagram
![img.png](imgs/architecture.png)


---

## ⚙️ Setup Instructions

1. **Get your GROQ API key**  
   - Visit: [https://console.groq.com/keys](https://console.groq.com/keys)  
   - Create an API key and add it to your `.env` file located inside the `app/` directory:
     ```
     GROQ_API_KEY=your_api_key_here
     ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt

3. Run the Streamlit app
   - streamlit run app/main.py
