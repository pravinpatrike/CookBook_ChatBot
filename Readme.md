README.md Content:

# 🍳 Interactive Cookbook Chatbot

Welcome to the **Interactive Cookbook Chatbot**! This project is designed to help you easily extract information from online recipes, including the recipe title, ingredients, directions, and cooking tools used. Additionally, the chatbot provides a search function to help you find more information via Google or YouTube.

## 📋 Features

- **Extract Recipe Title:** Get the title of the recipe from the provided URL.
- **Extract Ingredients:** List all the ingredients used in the recipe.
- **Extract Directions:** Display step-by-step cooking instructions.
- **Analyze Tools Used:** Identify and list the cooking tools mentioned in the recipe.
- **Help with Search:** Perform a Google or YouTube search based on your query.

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Google Chrome installed on your system

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/interactive-cookbook-chatbot.git
    cd interactive-cookbook-chatbot
    ```

2. **Install the required Python packages**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Download the spaCy language model**:

    ```bash
    python -m spacy download en_core_web_md
    ```

4. **Run the chatbot**:

    ```bash
    python chatbot.py
    ```

### Usage

- Enter the URL of the recipe you want to analyze.
- Choose an option from the menu to extract and view different information from the recipe.
- You can also search for additional information using Google or YouTube.

### Example

```bash
👋 Hello! Welcome to the Interactive Cookbook Chatbot!
Please enter the recipe URL: https://www.example.com/recipe-url

📜 Menu:
1️⃣ Show Title
2️⃣ Show Ingredients
3️⃣ Show Directions
4️⃣ Show Tools Used
5️⃣ Help
6️⃣ End
```

## 🛠️ Built With

- Python
- BeautifulSoup (for parsing HTML)
- Selenium (for web scraping)
- spaCy (for natural language processing)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ✨ Acknowledgments

- [spaCy](https://spacy.io/) - Natural Language Processing library used for analyzing text.
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) - Python library used for web scraping.
- [Selenium](https://www.selenium.dev/) - Tool for automating web browsers.
