# Recommendation Engine Prototype

This project implements an AI-powered recommendation engine for an e-commerce platform.

## Features
- **Data Analysis:** The system performs comprehensive data analysis on the e-commerce dataset, including visualizations of price distribution across top categories and discount percentage distribution.
- **Product Recommendation:** Users can input their preferences, such as product department, category, brand, and maximum price range, and the system generates personalized product recommendations based on their input.
- **NLP-powered Search:** The system utilizes NLP techniques to understand user queries and provide relevant product suggestions.
- **Efficient Data Processing:** The dataset is preprocessed and tokenized to extract relevant information and create a vector store for efficient retrieval of product recommendations.
- **Persistent Storage:** The processed data and vector store are saved to disk, eliminating the need for repeated data processing and reducing API call costs.
- **Interactive UI:** The system features an intuitive and user-friendly interface built with Streamlit, allowing users to easily interact with the recommendation system.

## Quick Start

Run the following commands to set up and start the recommendation engine:

```bash 
# Clone the repository (replace with your actual repository URL)
git clone https://github.com/Milansojitra/Trilogy-Recommendation.git
cd recommendation-engine

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt


#Add your OpenAI API key to the .env file in the following format:
OPENAI_API_KEY=your-api-key

# Run the application
streamlit run app.py
