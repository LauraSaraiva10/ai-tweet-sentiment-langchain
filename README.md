# AI Tweet Creator & Sentiment Analysis & LangChain

This repository contains a Python-based project that leverages OpenAI’s GPT model and LangChain to perform multiple tasks:

1. **AI Tweet Creator**: A Python-based tool for generating tweets using OpenAI's GPT model.
2. **Sentiment Analysis**: Analyze the sentiment (positive, negative, or neutral) of generated tweets.
3. **LangChain Example**: A Python-based example demonstrating the use of LangChain with OpenAI to chain tasks, such as generating equations and providing explanations.

---

## 🚀 Projects

### 1. **AI Tweet Creator / Sentiment Analysis**

This project leverages OpenAI's GPT model to create and analyze tweets. Given a topic, it generates a tweet and performs sentiment analysis (positive, negative, or neutral) on the generated tweet. The sentiment analysis also includes an emoji based on the sentiment.

- **Features**:
  - **Tweet Generation**: Create tweets about a specified topic with a configurable length.
  - **Sentiment Analysis**: Analyze the sentiment of the generated tweet and display the result with an emoji.

---

### 2. **LangChain Example**

This project demonstrates how to use **LangChain** to chain tasks in Python. Specifically, it shows how to generate a mathematical equation based on a description and then explain the equation in Python code. The **SimpleSequentialChain** from LangChain is used to link the tasks sequentially.

- **Features**:
  - **Mathematical Equation Generation**: Generate a mathematical equation based on a user-defined description.
  - **Explanation of Code**: Generate an explanation of the equation and the corresponding Python code.

---

## 🛠️ Requirements

Both projects require the **OpenAI API**. Ensure you have your OpenAI API key set up as an environment variable: `OPENAI_API_KEY`

## 🤝 Acknowledgments

OpenAI GPT: Used for generating tweets, analyzing sentiment, and creating mathematical equations.

LangChain: Used to chain tasks for generating and explaining equations.