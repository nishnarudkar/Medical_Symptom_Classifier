# Medical Symptom Classifier

A conversational AI agent for medical symptom classification, leveraging LangGraph (an extension of LangChain) to build a stateful, multi-step reasoning system. This project demonstrates how to structure complex agent flows, integrate external tools, and optionally provide a web-based chatbot interface.

---

## ✨ Features

- **Multi-step Agent Graph:** Uses LangGraph to define a conversational loop between agent and user, enabling complex reasoning and clarification.
- **Tool Integration:** Supports integration with calculators (via SerpAPI or similar), enhancing the agent’s capabilities.
- **Dynamic State Tracking:** Maintains and updates conversation state using a graph node system for robust multi-turn interactions.
- **Streamlit UI (Optional):** Easily connect with Streamlit to offer a web-based chatbot interface.

---

## 🚀 How It Works

1. **Agent Node:** Utilizes an LLM (e.g., OpenAI) to plan actions, generate responses, and optionally call integrated tools.
2. **User Node:** Displays intermediate outputs and feeds user/agent responses back into the agent until a final answer is reached.
3. **Graph Execution:** The flow continues in a loop until the agent indicates the conversation is complete or a final answer is generated.

---

## 📓 Notebook Overview

The included Jupyter Notebook covers:

- Setting up the OpenAI model and tool integrations.
- Creating a LangGraph-based conversational flow.
- Managing dynamic state and controlling transitions between steps.
- Running and testing the multi-step reasoning agent.

---

## 🧰 Requirements

Install the dependencies with:

```bash
pip install langgraph langchain openai streamlit
```

- You will need API keys for OpenAI (and optionally SerpAPI or other tools).

---

## ⚙️ Usage

**In Python:**

```python
import openai
import langgraph
# Load your agent and graph according to the notebook or your script
# Run the graph to start the conversational agent
```

**Or use the provided Jupyter Notebook:**

```bash
jupyter notebook Nishant_langgraph.ipynb
```


## 📷 Screenshots

Add screenshots or GIFs of the chatbot interface or graph outputs here to demonstrate functionality.

---

## 🤝 Contributing

Contributions are welcome! Please open issues or submit PRs for suggestions and improvements.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## ⭐ Show Your Support

If you found this project helpful, please consider starring ⭐ the repository!

---

**Contact:**  
For questions or support, please open an issue on GitHub.

---

Let me know if you want sections on FAQ, troubleshooting, or example conversations!
