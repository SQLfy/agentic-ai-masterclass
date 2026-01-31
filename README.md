# Class 01: Foundations of Agentic AI

This module introduces the core concepts of Agentic AI, moving from simple LLM calls to building reasoning agents with tools, memory, and planning capabilities.

## 📂 Notebooks Overview

| File | Topic | Description |
| :--- | :--- | :--- |
| **1-LLMBasics.ipynb** | *LLM Capabilities* | Demonstrates what raw LLMs can do (generate text) vs. what they *cannot* do (access live data, take actions). |
| **2-SimpleAgent.ipynb** | *Your First Agent* | Builds a basic agent that uses a "customer history" tool to write personalized emails. |
| **3-Reasoning_etc.ipynb** | *Core Components* | Explores individual agentic components: Chain-of-Thought reasoning, Memory management, and Tool use. |
| **4-Reflection.ipynb** | *Reflection Pattern* | Implements a "Writer-Critic" loop where an agent critiques and improves its own work. |
| **5-Planner.ipynb** | *Planning Pattern* | A specific "Planner" agent that breaks a complex request into steps and executes them sequentially. |
| **6_ticket_triage.ipynb** | *End-to-End System* | A complete "Ticket Triage" system using RAG, classification, and routing to handle support tickets. |

## 🛠️ Quick Start

1.  **Install Dependencies:**
    ```bash
    pip install langchain langchain-openai langgraph python-dotenv
    ```
2.  **Set API Key:**
    Create a `.env` file in this folder:
    ```text
    OPENAI_API_KEY="sk-..."
    ```
3.  **Run:** Start with `1-LLMBasics.ipynb` and work your way through to the final system in notebook 6.

***

### **Instructor Notes**
* **Notebooks 1-3** cover the basics (The "What" and "How").
* **Notebooks 4-5** introduce specific agentic *patterns* (Reflection, Planning).
* **Notebook 6** is the capstone project for this class.