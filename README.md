# Food Dictionary & Culinary Explorer

![Cuisine Banner](https://slofoodbank.org/wp-content/uploads/2023/07/Food-as-Culture.png) <!-- Replace with actual image -->

A conversational AI-powered food dictionary that explores recipes, cultural backgrounds, and historical contexts of dishes from around the world.

## Features

- 🍲 **Recipe Discovery**: Get detailed recipes for traditional dishes
- 🌍 **Cultural Insights**: Learn about the cultural significance of foods
- 📜 **Historical Context**: Discover the origins and evolution of dishes
- 🔍 **Multi-source Knowledge**: Combines AI with verified information from Wikipedia
- 💬 **Interactive Chat**: Natural language interface for food exploration

## Technologies Used

- **LangChain** - AI agent framework
- **Google Gemini** - Large Language Model (gemini-1.5-flash)
- **Wikipedia API** - For verified factual information
- **Gradio** - Web interface
- **Python** - Backend logic
- Visual Studio Code (VS Code)
- [Poetry](https://python-poetry.org/) for dependency management (optional but recommended)


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/madalina889/food-dictionary.git
   cd food-dictionary
   Install dependencies:
bash
pip install -r requirements.txt
Set up your environment:
Create a .env file
Add your Gemini API key:
GEMINI_API_KEY=your_api_key_here
Usage

Run the application:

bash
python app.py
Then open your browser to http://localhost:7861 to access the web interface.

Example queries:

"Tell me about the history of ramen"
"Give me a traditional recipe for coq au vin"
"What's the cultural significance of tacos in Mexico?"
"Explain how pizza evolved in different countries"
Project Structure

food-dictionary/
├── app.py                # Main application file
├── requirements.txt      # Python dependencies
├── .env                  # Environment variables
├── README.md             # This file
└── assets/               # Optional: for images/screenshots
Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements.

Note: This application requires a valid Google Gemini API key to function properly.


### Key Features of This README:

1. **Professional Structure**: Follows standard GitHub project documentation format
2. **Visual Appeal**: Includes space for banner image and emojis for better readability
3. **Comprehensive Sections**: Covers all essential information for users and contributors
4. **Clear Instructions**: Step-by-step setup and usage guide
5. **Example Queries**: Helps users understand how to interact with your app
6. **Responsive Design**: Renders well on GitHub's markdown viewer

🧠 Features
Cuisine Information: Ask about various cuisines, and the assistant will provide details.

History of Dishes: Inquire about the history of specific dishes.

Interactive Interface: Utilize Gradio for a user-friendly chat interface.

⚠️ Deprecation Notice
The initialize_agent method from LangChain is deprecated. It's recommended to use LangGraph's prebuilt agents for new projects. For more information on migrating to LangGraph, refer to the LangChain Migration Guide.

