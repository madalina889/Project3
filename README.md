🥘 Food Dictionary AI

Food Dictionary AI is an interactive Python-based project powered by LangChain and Google's Gemini API that allows users to:

🔍 Search for dishes by cuisine
📜 Learn the historical background of a dish
🍽️ Get a list of recipes and ingredients
🛒 Generate shopping lists for selected recipes (coming soon)
This project integrates large language models and food-related APIs to build an intelligent, conversational food encyclopedia.

🚀 Features

Cuisine Exploration: Enter a cuisine (e.g., "Turkish") to get a list of traditional dishes.
Dish History: Ask for the origin, history, and cultural context of any dish.
Recipe Fetching: Use APIs like Spoonacular or TheMealDB to get detailed recipes.
Future Add-ons:
Automated meal planning
Ingredient substitution
Calorie and nutritional info
Voice input/output support
🧠 Powered By

LangChain
Gemini (Google Generative AI)
Spoonacular API
TheMealDB API
📁 Project Structure
food-dictionary-ai/
├── food_dictionary_notebook.ipynb  # Main notebook with code and logic
├── requirements.txt                # Dependencies
└── README.md                       # Project documentation
🔧 Installation

1. Clone the repository
git clone https://github.com/yourusername/food-dictionary-ai.git
cd food-dictionary-ai
2. Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows use `env\\Scripts\\activate`
3. Install dependencies
pip install -r requirements.txt
4. Set up your .env file
GEMINI_API_KEY=your_google_generative_ai_key
RECIPE_API_KEY=your_spoonacular_or_themealdb_key
💡 How It Works

The notebook uses:

LLM (Gemini via LangChain) to interpret questions and generate responses
CommaSeparatedListOutputParser to format results into user-friendly lists
Wikipedia & Meal APIs to retrieve real-time data about food
📸 Sample Use Cases

Example 1: Explore Cuisine
Which cuisine do you want to know about?
> Turkish
Outputs:

Popular appetizers, mains, desserts
Cultural context
Example 2: Historical Info
Tell me about history of:
> Adana Kebabı
Outputs:

Origin city
Traditional preparation
Cultural significance
⚠️ Disclaimer

This project is intended for educational purposes and may not always provide accurate or up-to-date information. Use verified sources when cooking or sharing dietary information.
📜 License

MIT License

