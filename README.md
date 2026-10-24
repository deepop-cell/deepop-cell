# Hi, I'm Deep 👋

**Second-Year Undergraduate at IIT Kharagpur | Aspiring Software Development Engineer**

I am a second-year UG student focusing on backend development, algorithmic problem-solving, and building scalable applications. I am actively preparing for SDE internships, with a strong foundation in data structures, API architecture, and integrating local AI models into practical workflows.

## 🚀 What I'm Working On
* Building robust backend systems and RESTful APIs using Python and FastAPI.
* Developing and fine-tuning an interactive, local AI streaming assistant with parallel tool-calling capabilities.
* Prototyping and deploying frontend architectures using React, TypeScript, and Vite on Vercel.

## 💻 Tech Stack
* **Languages:** C++, Python, TypeScript, SQL
* **Backend & Frameworks:** FastAPI, Object-Oriented Programming (OOP)
* **Frontend:** React, Vite
* **AI & Integration:** OpenAI Python SDK, Ollama, LLM Tool Calling
* **Tools & Deployment:** Git, Vercel, VS Code

## 🏆 Algorithmic Problem Solving
* **LeetCode:** 700+ problems solved (including 150+ from Striver's SDE sheet). Specializing in advanced topics like Dynamic Programming (top-down memoization), Graphs (Kosaraju's algorithm, DSU), Trees, and Bit Manipulation.
* **Codeforces & CSES:** Focused on rigorous algorithmic problem-solving. Actively upsolving on Codeforces using first-principles mathematical reduction for complex logic puzzles, and mastering classical algorithmic patterns via the CSES problem set.

## 📂 Featured Projects

### Local AI Streaming Assistant
A robust, Python-based CLI application that interfaces with local LLMs via Ollama and the OpenAI Python SDK to create an interactive, autonomous agent. Features include:
* **Real-Time Token Streaming:** Implements continuous chunk streaming with `flush=True` for a zero-latency, ChatGPT-like terminal experience.
* **Autonomous Chain-Tool Calling:** Features a custom iterative loop (`MAX_STEPS`) that parses interleaved JSON argument chunks using `SimpleNamespace`, executes the mapped Python functions, and injects the results back into the model's context for multi-step reasoning.
* **Robust State Management:** Maintains persistent multi-turn chat history and dynamically builds nested dictionary payloads (`"type": "function"`) to strictly adhere to OpenAI API schema requirements.
* **Graceful Interrupt Handling:** Integrates a `try-except KeyboardInterrupt` block, allowing users to instantly halt long text generations or tool loops without crashing the script or losing the conversation state.
* **Dynamic System Personas:** Supports injecting custom, highly specific system prompts to alter the agent's behavior and bypass standard alignment constraints during local testing.

### AI-Driven Multi-Vendor Security Auditor (SIH 2026)
* Developed as part of Team PHELKROS for the Smart India Hackathon internal round.
* Built a standalone cybersecurity dashboard prototype using React and TypeScript.
* Packaged and deployed the frontend interface seamlessly via Vercel.

## 📫 Get in Touch
* **Email:** deeppandey25@kgpian.iitkgp.ac.in
* **LinkedIn:** https://www.linkedin.com/in/deep-pandey-69a0b13b2/
* **LeetCode:** https://leetcode.com/u/naughty_deep1499/
