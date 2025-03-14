# GenBI: AI-Powered Business Data Analysis & Visualization

## 🚀 Hackathon Project - AI-driven Business Intelligence for E-commerce Analytics

&#x20;&#x20;

## 📌 Project Overview

**GenBI** (Generative Business Intelligence) is an interactive **AI model** designed for **business data analysis**, visualization, and LLM benchmarking. Developed as part of a **hackathon**, this project analyzes **Blinkit Sales Dataset** using **LangChain multi-agent architecture**, **LLMs**, and **automated EDA** to generate data-driven insights.

## 🔥 Key Features

- **📊 Automated Exploratory Data Analysis (EDA):** Generates statistical insights and suggests **top 3 charts** based on dataset structure.
- **🤖 Multi-Agent AI System:** Implements **LangChain-powered agents** for **data cleaning, analysis, visualization, and LLM benchmarking**.
- **⚡ LLM Benchmarking:** Compares **GPT-4, Gemini, and open-source models** for business queries.
- **📈 AI-Driven Visualizations:** Generates **bar charts, scatter plots, box plots, heatmaps**, etc.
- **🛠️ Customizable & Extendable:** Modular design allows easy **dataset integration** and **custom agent expansion**.

---

## 📂 Dataset
- Blinkit Sales Dataset (E-commerce Grocery Sales) https://www.kaggle.com/datasets/akxiit/blinkit-sales-dataset

📌 **Additional datasets can be integrated into GenBI.**

---

## 🏗 Tech Stack

| **Technology**                 | **Purpose**                                 |
| ------------------------------ | ------------------------------------------- |
| **Python**                     | Core programming language                   |
| **LangChain**                  | Multi-agent system for AI automation        |
| **OpenAI API**                 | GPT-4 / GPT-4-turbo / GPT-3.5 for LLM tasks |
| **Google Gemini**              | Alternative LLM for comparison              |
| **Open-Source LLMs**           | Hugging Face-based models for benchmarking  |
| **Pandas / NumPy**             | Data preprocessing and analysis             |
| **Matplotlib / Seaborn**       | Data visualization                          |
| **Hugging Face Inference API** | Model hosting for free-tier LLMs            |
| **Pinecone**                   | Vector storage for memory-based retrieval   |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/GenBI.git
cd GenBI
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv env
source env/bin/activate  # Mac/Linux
env\Scripts\activate  # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Set Up API Keys

Create a `.env` file in the root directory and add the following:

```
OPENAI_API_KEY=your_openai_api_key
GOOGLE_API_KEY=your_google_gemini_api_key
PINECONE_API_KEY=your_pinecone_api_key
HUGGINGFACE_API_KEY=your_huggingface_api_key
```

### 5️⃣ Run the Chatbot

```bash
python main.py
```

---

## 🎯 How It Works

1. **Upload your dataset** (CSV format).
2. **Chat with GenBI**:
   - Ask about **data trends**, **insights**, or request an **EDA**.
   - Example queries:
     ```
     - "Can you do an EDA on this dataset?"
     - "What's the average price of fruits?"
     - "Compare price trends across product categories."
     ```
3. **Dynamic Agent Activation**:
   - **Data Cleaning Agent** → Fixes missing values, duplicates.
   - **Data Analysis Agent** → Handles queries like *"max price of dairy products?"*.
   - **Data Visualization Agent** → Generates relevant charts based on query.
   - **LLM Comparison Agent** → Benchmarks OpenAI vs Gemini vs OSS models.

---

## 🏆 Hackathon Achievements

- **Developed in a one-week sprint** with **LLM-driven EDA & visualization.**
- **Successfully integrated multi-agent automation** to handle diverse business queries.
- **Compared multiple LLMs** for business intelligence tasks.

---

## 🔥 Future Enhancements

✅ **Support for live data streams** (e.g., real-time Blinkit sales trends).\
✅ **More LLMs** (e.g., Claude, Mistral) for better benchmarking.\
✅ **Fine-tuned industry-specific LLM agents** for e-commerce.

---

## 🤝 Contributing

We welcome contributions!\
📌 **Fork the repo**, **create a branch**, and **submit a PR**.

---

## 📜 License

This project is licensed under the **MIT License**.

---

🚀 **Built for AI-driven Business Intelligence & Data Analytics.**\
🎯 **Designed for Hackathons & Real-World Business Use Cases.**

