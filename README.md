# 🎓 Improved-LLM-Tutor

[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-green.svg)](https://openai.com/)
[![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-orange.svg)](https://ollama.ai/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

An intelligent multi-model tutoring system that leverages GPT-4 and Llama3.2 to provide comprehensive technical education with real-time response comparison and performance analytics.

## 📸 Live Demo

### Side-by-Side Model Comparison
![image](https://github.com/user-attachments/assets/ab66ed0b-e356-477f-93ab-1fb30a0ca82b)
*Compare how GPT-4o-mini and Llama3.2 approach the same programming question*

### Real-Time Response Streaming
![Animation](https://github.com/user-attachments/assets/189c6011-4741-404b-ba62-b1ebcdaae99f)
*Watch as AI models think through problems in real-time with formatted markdown*

## ✨ Key Features

🤖 **Dual AI Integration** - Seamlessly combines OpenAI GPT-4o-mini with Ollama's Llama3.2  
📊 **Side-by-Side Comparison** - Visualize how different AI models approach the same problem  
⚡ **Real-Time Streaming** - Watch responses unfold with live markdown rendering  
📈 **Performance Analytics** - Track and visualize response times with built-in metrics  
💾 **Persistent Sessions** - Save and reload conversation history for continuous learning  

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- OpenAI API key
- Ollama installed locally (for Llama3.2 model)

```bash
# Clone the repository
git clone https://github.com/simondb94/Improved-LLM-Tutor.git
cd Improved-LLM-Tutor

# Install dependencies
pip install openai ollama pandas matplotlib rich python-dotenv ipython

# Set up your OpenAI API key
echo "OPENAI_API_KEY=your_api_key_here" > .env

# Run the notebook
jupyter notebook Improved_LLM_Tutor.ipynb
```

## 💡 Usage Example

```python
# Initialize the tutor
tutor = LLMTutor()

# Ask a question to both models
responses = tutor.ask("Explain binary search algorithm in Python")

# Compare responses side-by-side
tutor.compare_responses()

# View performance metrics
tutor.show_performance_metrics()
```

## 📊 Performance Insights

![Animation](https://github.com/user-attachments/assets/2eeaada5-0927-4f16-bcfc-7a50d404ad35)
*Real performance data: GPT-4o-mini (~12s) vs Llama3.2 (~44s) response times*

## 🎯 Real-World Example

Here's how the tutor handles a practical coding question:

![image](https://github.com/user-attachments/assets/21d0affa-4675-461e-8021-e889f8194c1f)

**Question**: "Given a list of dictionaries called 'books', write code to find and print all information about the book titled 'Mastery' by Robert Greene."

The system provides two different approaches:
- **GPT-4o-mini**: Focuses on safe dictionary access with `.get()` method and comprehensive error handling
- **Llama3.2**: Demonstrates both basic implementation and extended use cases with list comprehensions

## 🛠️ Tech Stack

- **Core**: Python 3.8+, IPython, Jupyter
- **AI Models**: OpenAI API (GPT-4o-mini), Ollama (Llama3.2)
- **Visualization**: Rich Console, Matplotlib, Pandas
- **Display**: IPython.display for real-time markdown rendering
- **Utilities**: python-dotenv, JSON persistence

## 🌟 Key Differentiators

✅ **Multiple Perspectives**: See how different AI models approach the same problem  
✅ **Production-Ready**: Clean architecture with error handling and logging  
✅ **Performance Tracking**: Built-in analytics to understand model efficiency  
✅ **Developer-Friendly**: Intuitive API design with comprehensive documentation  

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 📬 Connect

**Built with ❤️ by Simon D. Boal**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue.svg)](https://www.linkedin.com/in/simon-d-boal-b03b8b70)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black.svg)](https://github.com/simondb94)

---

![image](https://github.com/user-attachments/assets/92846e52-4693-488b-9364-520cc92c0595)
