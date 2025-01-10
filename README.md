# **Social Media Performance Analysis**

This project is part of the **Pre-Hackathon Assignment** for the **Level Supermind Hackathon**. The objective is to develop a basic analytics module using **Langflow**, **DataStax Astra DB**, and the **meta/llama-3.1-405b-instruct** LLM to analyze social media engagement data from mock accounts.

---

## **Objective**

1. **Synthetic Data Generation**: Use an advanced LLM to generate synthetic social media engagement data (likes, shares, comments, etc.) for various post types (carousel, reels, static images).
2. **Data Storage**: Store generated engagement data in **DataStax Astra DB** for efficient querying and analysis.
3. **Insights Generation**: Use Langflow with **meta/llama-3.1-405b-instruct** for:
   - Generating actionable insights on post performance.
   - Simulating chatbot-style responses to user queries.
   - Code generation for advanced data analysis.

---

## **Tools & Technologies**

- **Langflow**: For orchestrating the workflow and integrating different components.
- **DataStax Astra DB**: For storing and querying synthetic social media engagement data.
- **meta/llama-3.1-405b-instruct**: A state-of-the-art LLM used for:
  - **Synthetic Data Generation**: Creating mock engagement data.
  - **Chatbot Responses**: Providing intelligent, conversational insights.
  - **Code Generation**: Assisting in domain-specific data analysis and reporting.
- **Cohere Embeddings**: For generating text embeddings used in vector similarity tasks.
- **Python**: To load and run the Langflow workflow.

---

## **Langflow Workflow Components**

1. **Chat Input**: Accepts user queries related to social media analytics.
2. **Astra DB**: Connects to the DataStax Astra DB instance and retrieves relevant data.
3. **Cohere Embeddings**: Generates vector embeddings for natural language processing tasks.
4. **Agent**: Powered by **meta/llama-3.1-405b-instruct**, handles:
   - Query interpretation.
   - Data analysis and generation of insights.
   - Code generation for complex tasks.
5. **Prompt & Parse Data**: Prepares and formats the data to generate coherent insights.
6. **Chat Output**: Displays the insights in a conversational format.

---

## **How to Run the Project**

### **Step 1: Clone the Repository**

```bash
git clone https://github.com/arjunthilak05/social-media-performance-analysis.git
cd social-media-performance-analysis
```

### **Step 2: Set Up Python Environment**

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### **Step 3: Run the Script**

```bash
python main.py
```

---

## **Capabilities of meta/llama-3.1-405b-instruct**

This project leverages the **meta/llama-3.1-405b-instruct** model, an advanced large language model, for:

1. **Synthetic Data Generation**:
   - Generates mock social media engagement data for posts.
2. **Chatbot-Style Insights**:
   - Provides interactive responses on post performance and engagement metrics.
3. **Code Generation**:
   - Assists with on-the-fly generation of analysis scripts for advanced users.

### **Disclaimer**

The **meta/llama-3.1-405b-instruct** model may produce outputs that are inaccurate, biased, or inappropriate. Users are advised to test the model thoroughly before deploying it in production environments.

---

## **Project Structure**

```
social-media-performance-analysis/
├── README.md                # Project documentation
├── requirements.txt         # Python dependencies
├── app.py              # Main script to execute Langflow workflow
├── socialflow.json  # Langflow JSON workflow file
└── dashboard.html
└── analytics.html
└── socialmediadummy.csv 
```

---

## **Demo Video**

Watch the project demo video on [YouTube](<your-demo-video-link>).

---

## **Submission Details**

- **Hackathon:** [Level Supermind Hackathon](https://www.findcoder.io/hackathons/SuperMind-Hackathon/67668c927a79c23209528177)
- **GitHub Repository:** [Link to Repository](https://github.com/arjunthilak05/social-media-performance-analysis.git)  
- **Demo Video:** [Link to Demo Video](<your-demo-video-link>)  

---

## **Contributors**

- **R Arjun Thilak ** – *Developer*

---

## **License**

This project is licensed under the MIT License.

---

