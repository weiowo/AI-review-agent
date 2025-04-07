# AI Review Agent

An intelligent Python agent that answers user questions based on a dataset of reviews.  
Powered by **LangChain**, **Ollama**, **Chroma**, and **Pandas**, this lightweight AI system uses a CSV file as its data model and provides answers using locally hosted language models.

---

## Requirements

Make sure you have Python 3.9+ and [Ollama](https://ollama.com) installed and running on your machine.

---

## Quick Start

1. **Clone this repo & navigate into it:**

   ```bash
   git clone <your-repo-url>
   cd ai-review-agent
   ```

2. **Install dependencies:**

   ```pip install -r requirements.txt```

3. **Run the agent:**

   ```python main.py```

4. **Ask your question:**

   ```Ask your question (q to quit): 
   (for example: How is the ambiance of the restaurant?)
   ```

---

## Project Structure

.
├── main.py                          # Main chat loop
├── vector.py                        # Vector store setup and retriever logic
├── realistic_restaurant_reviews.csv  # Review data source
├── requirements.txt                 # Required packages
└── README.md                        # Project instructions
