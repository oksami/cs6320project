# Green Portfolio – ESG Chatbot for Ethical Investing
## CS 6320
## By: Anupa Desai, Samhita Kadali
### Overview
The ESG Chatbot is a command-line-based assistant designed to help users explore ESG (Environmental, Social, and Governance) compliant investment opportunities. It provides fund recommendations, sentiment analysis for major companies, and visualizations for comparing ESG ratings.
### Link to Youtube
https://www.youtube.com/watch?v=PUTBbzHYECo
#### The chatbot leverages Protege ontology for fund classification, rule-based intent recognition, and dynamic querying capabilities.

### Functionalities
#### Fund Recommendations:

1. Choose specific ESG criteria like fossil-free, deforestation-free, prison-free, gun-free, weapon-free, gender equality, and tobacco-free funds.
2. Specify grades (A, B, C, D, E, F) to tailor your recommendations.
Sentiment Analysis:

#### Analyze sentiment for major companies based on ESG-related news.
#### ESG Visualizations:

Compare and visualize the ESG ratings of different companies.
## Project Files
### Python Files:
1. Intent_Recognition.py: Identifies user intent (recommendation, sentiment analysis, visualization).
2. process_query.py: Extracts the specific ESG criteria and grade from user queries.
3. Protege_query.py: Queries the Protege ontology to retrieve funds matching the given criteria and grade.
4. sentimentAnalysis.py: Performs sentiment analysis and generates visualizations for ESG comparisons.
## Data Folder Contains:
1. ESG scores for major companies.
2. Individual CSV files for each ESG criterion (fossil-free, deforestation-free, etc.).
3. The cleaned dataset used for querying.
4. The Protege ontology (Protege_project.rdf).
## Other Files
1. BERT_Model_&_Testing.ipynb: Demonstrates BERT-based intent recognition (not used in the chatbot) and extracts fund directly from  the csv file based on fund criteria.
2. Data_Preprocessing.ipynb: Processes and cleans data (not required during chatbot execution).
3. chatbotDemo.mp4: A short demo video showcasing the chatbot's functionalities.
## How to Run the Chatbot
### Method 1: Using Integrated_chatbot.ipynb
1. Use the folder: https://drive.google.com/drive/folders/1GK3cIgwrFVjkNEwoELFyQfUHylC1pqME?usp=sharing
2. Open the Integrated_chatbot.ipynb notebook in your preferred environment (e.g., Google Colab or Jupyter Notebook).
3. Run all cells sequentially.
4. Interact with the chatbot directly in the notebook.
### Method 2: Using main_chatbot.py
1. Clone the repository:
2. Ensure all dependencies are installed:
3. Run the chatbot directly using main_chatbot.py
4. Interact with the chatbot through the terminal.
### Additional Notes
The Protege ontology is preloaded in the chatbot for dynamic querying, so there's no need to preprocess data manually.
## Lessons Learned and Future Work
### Lessons Learned:
1. Leveraging ontologies enhanced data efficiency and scalability.
2. A rule-based approach was more effective for intent recognition compared to BERT due to the limited dataset.
### Future Work:
1. Explore RNN-based classifiers for intent recognition.
2. Expand the ontology to include synonyms for better query mapping.
3. Integrate fund performance metrics using external APIs.

