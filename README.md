# Medical_Symptom_Classifier

This project demonstrates a simple yet powerful conversational agent using LangGraph, which extends LangChain for building stateful, multi-step language agents as graphs.

✨ Features
Multi-step agent graph: Uses LangGraph to define a flow where an agent and a user interact in a loop until a final answer is generated.

Tool integration: Supports tools such as a calculator (via serpapi or similar approach) to enhance responses.

Dynamic state tracking: Maintains and updates conversation state using a graph node system.

Streamlit UI (optional): Can be easily integrated with Streamlit for a web-based chatbot interface.

🚀 How It Works
1️⃣ The agent node uses an LLM (here, OpenAI) to plan actions and optionally call tools.
2️⃣ The user node takes the intermediate agent outputs, displays them, and feeds them back into the agent until completion.
3️⃣ The graph continues until the agent indicates it has a final answer.

📄 Notebook Overview
The notebook covers:

Setting up an OpenAI model and tool definitions.

Creating a graph with LangGraph to handle interaction flow.

Managing state and controlling transitions.

Running and testing the graph step by step.

🧰 Requirements
bash
Copy
Edit
pip install langgraph langchain openai streamlit
You may also need keys for OpenAI (and optionally for SerpAPI or other tools).

⚙️ Usage
import openai
import langgraph
# Load your agent and graph
# Then run as shown in the notebook

Or simply run the Jupyter Notebook:
jupyter notebook Nishant_langgraph.ipynb

📷 Screenshots
💡 You can add screenshots or GIFs of the graph outputs or chatbot interface here.

🤝 Contributing
Contributions are welcome! Please open issues or submit PRs for improvements.

📄 License
MIT License

⭐ Show some ❤️
If you find this project helpful, please ⭐ star the repository!

