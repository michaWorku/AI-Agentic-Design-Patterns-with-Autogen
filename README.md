# AI Agentic Design Patterns with AutoGen


## 📘 Course Overview

[**AI Agentic Design Patterns with AutoGen**](https://www.deeplearning.ai/short-courses/ai-agentic-design-patterns-with-autogen/) is a hands-on course designed by DeepLearning.AI to teach developers and AI practitioners how to design and implement **multi-agent systems** using the **AutoGen** framework. The course explores collaborative AI patterns such as tool use, planning, reflection, and conversation orchestration across real-world use cases like customer onboarding, blog writing, financial analysis, and more.


## 📚 Course Content

1. [**Introduction to AutoGen & Agentic Design Patterns**]()
   - Core components of AutoGen
   - Conversable agents and assistant agents

2. [**Multi-Agent Conversations & Stand-up Comedy**](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L1_Multi-Agent_Conversation_and_Stand-up_Comedy.ipynb)
   - Agent memory, multi-turn chat, custom termination logic
   - Summary generation with LLM reflection

3. [**Sequential Chats & Customer Onboarding**](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L2_Sequential_Chats_and_Customer_Onboarding.ipynb)
   - User proxy agents
   - Multi-step task orchestration and data extraction

4. [**Reflection & Blogpost Writing**](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L3_Reflection_and_Blogpost_Writing.ipynb)
   - Nested review systems
   - Role-specific feedback agents (SEO, Legal, Ethics)

5. [**Tool Use & Conversational Chess**](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L4_Tool_Use_and_Conversational_Chess.ipynb)
   - External tool calling with Python agents
   - Game logic orchestration and human participation

6. [**Coding & Financial Analysis**](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L5_Coding_and_Financial_Analysis.ipynb)
   - Agent-driven code generation and execution
   - Use of predefined helper functions

7. [**Planning & Stock Report Generation**](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L6-Planning_and_Stock_Report_Generation.ipynb)
   - Multi-role simulation: planner, engineer, executor, and writer
   - Admin-controlled iteration and report generation


## 📓 Notebooks

> _Each notebook includes runnable examples, task definitions, and AutoGen configurations._

- [1: Multi-Agent Comedy Chat](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L1_Multi-Agent_Conversation_and_Stand-up_Comedy.ipynb)  
- [2: Customer Onboarding Flow](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L2_Sequential_Chats_and_Customer_Onboarding.ipynb)  
- [3: Blog Writing with Feedback Loop](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L3_Reflection_and_Blogpost_Writing.ipynb)  
- [4: Chess Game with Tool Integration](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L4_Tool_Use_and_Conversational_Chess.ipynb)  
- [5: Financial Data Analysis via Code](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L5_Coding_and_Financial_Analysis.ipynb)  
- [6: Stock Report via Agent Workflow](https://github.com/michaWorku/AI-Agentic-Design-Patterns-with-Autogen/blob/main/L6-Planning_and_Stock_Report_Generation.ipynb)


## 🚀 Getting Started

### 1. **Environment Setup**
- Ensure Python 3.9+ is installed.
- Install dependencies:

```bash
pip install autogen openai matplotlib yfinance python-chess
```

### 2. **API Configuration**
- Set your OpenAI API key:
```python
from autogen import get_openai_api_key
get_openai_api_key()
```

### 3. **Run Notebooks**
- Open the desired notebook in Jupyter or VS Code.
- Execute cells sequentially to simulate agent interactions.


## 🔗 Resources and References

- [Official Course Link](https://www.deeplearning.ai/short-courses/ai-agentic-design-patterns-with-autogen/)
- [AutoGen GitHub Repo](https://github.com/microsoft/autogen)
- [OpenAI API Documentation](https://platform.openai.com/docs)
- [python-chess](https://python-chess.readthedocs.io/en/latest/)
- [yfinance Docs](https://pypi.org/project/yfinance/)


## 🛠 Helpers & Utils

Some lessons include predefined helper functions for enhanced code execution:

- `get_stock_prices(ticker, period)`: Fetches historical closing prices using `yfinance`.
- `plot_stock_prices(data, output_path)`: Plots and saves visualizations using `matplotlib`.
- `get_legal_moves()`, `make_move(move)`: Chess logic tools for move validation and board updates.

These helpers are **injected into the code execution environment** for better modularity, reducing LLM errors and increasing execution consistency.


Enjoy building powerful agentic workflows with **AutoGen**!
