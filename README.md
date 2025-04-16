# 🌐 MIMIR: Local LLM Based Teacher with Langflow

MIMIR is a modular flow built using [Langflow](https://github.com/logspace-ai/langflow) that helps you extract structured information from web pages. It takes one or more URLs, fetches their content, and passes it through a language model-powered agent to return meaningful insights — like embedded links or raw data.

---

## 🚀 Features

- 🔗 Load and parse content from any URL
- 🧠 AI-powered prompt logic to extract useful details
- 📊 Outputs include plain text, message format, or structured data (DataFrame)
- 💬 Optionally remembers previous sessions with memory integration

---

## 🛠️ Prerequisites

- Python 3.10+
- Langflow (`pip install langflow`)
- API key (for whichever LLM provider you choose — Google, OpenAI, etc.)

---

## ⚙️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mimir.git
   cd mimir
   ```

2. Launch Langflow:
   ```bash
   langflow run
   ```

3. Open your browser and go to `http://localhost:7860`

4. Import `MIMIR.json` into the Langflow UI and hit **Run**

---

## 🧪 How to Use

- Provide one or more URLs in the **URL** component  
- Choose between **Text** or **Raw HTML** output  
- The agent processes the data and gives you the results in structured or textual format  
- Make sure to add your API key (e.g., for Google Gemini) when configuring the agent

---

## 📜 License

MIT License

---
