# 🤖 Gemini AI Agent

An intelligent Python-based agent built using the **Google Gemini API**. This project demonstrates an AI agent's ability to navigate a local directory, read file contents, and autonomously write code fixes using function calling.

##  Features
* **Gemini API Integration:** Powered by Google's latest LLM models for reasoning.
* **Autonomous File Operations:** The agent can search, read, and write files to solve complex tasks.
* **Agentic Workflow:** The system uses a "Plan-Act-Verify" loop to ensure tasks are completed correctly.

---

##  Installation & Setup

1. **Clone the Repository
   ```bash
   git clone https://github.com/your-username/ai_agent.git
   cd ai_agent

2. **Install Dependcies 
   ```bash
   pip install -r requirements.txt

3. **Configure API Keys
   * **Obtain an API key from Google AI Studio.

   * **Create a file named .env in the project root.

   * **Add your key to the file:
  plaintext:GEMINI_API_KEY="your_api_key_here"


## Demo
Here I created a bug in the calculator.py that was cause calculations to be wrong and setting the addition to the highest precedence. 
With Gemini I am able to tell it to fix the bug. It is able to use the functions specified and find the bug and write the bug fix to the file. 

<p align="center">
  <img src="img_src/ai_agent%20(1).gif" alt="AI Agent Demo" width="1080">
</p>



##  What I Learned
Through the development of this project, I gained hands-on experience with:

* **Gemini API: Implementing function calling and managing stateful conversations.

* **Agentic Logic: Designing a system that can interpret its own environment and take actions.

* **System Pathing: Managing Python module imports and directory structures for complex projects.






