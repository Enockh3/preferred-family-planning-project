# Preferred Family Planning Project

This project analyzes data related to contraceptive use and discontinuation, aiming to uncover key factors influencing family planning preferences. It involves data cleaning, exploratory data analysis (EDA), machine learning modeling, and natural language processing (NLP) using OpenAI's language model.

## 📁 Project Structure

- `1_data_cleaning.ipynb`:  
  Preprocesses and cleans raw data, handles missing values, and prepares structured features for analysis.

- `2_exploratory_data_analysis.ipynb`:  
  Visualizes patterns in contraceptive use, explores relationships between demographic variables and method preference/discontinuation.

- `3_modeling.ipynb`:  
  Builds predictive models to identify patterns and trends related to contraceptive choices. Includes classification tasks and performance evaluation.

## 🤖 AI Integration (OpenAI NLP)

To handle open-text responses on reasons for stopping contraceptive use, the project uses **OpenAI's GPT model** for text classification:

- Unstructured responses were fed into the model using OpenAI's API.
- Responses were categorized into predefined classes (e.g., side effects, partner objection, access issues).
- This enriched the dataset and enabled deeper insights into user behavior and discontinuation reasons.

## 🔧 Tools & Technologies

- **Languages & Libraries**: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **AI/NLP**: OpenAI API (text classification)  
- **Environment**: Jupyter Notebook

## 🎯 Objectives

- Understand trends and discontinuation reasons for contraceptive use.
- Build models to predict factors influencing family planning choices.
- Apply LLM-based text classification to extract structured insights from open-ended survey responses.

## 📈 Outcomes

- Cleaned and structured complex survey data.
- Generated actionable visualizations for family planning trends.
- Applied machine learning and NLP to uncover drivers of contraceptive discontinuation.

## 📌 Notes

- The project uses **public health data** (source not included here).
- All personally identifiable information (PII) was excluded
- Text classification with OpenAI was done via a secure API and applied only to textual feedback fields.

## 💡 Future Work

- Deploy interactive dashboards using Streamlit or Flask.
- Extend NLP analysis to other health-related open-text survey data.
- Integrate local language (e.g., Kinyarwanda) classification using fine-tuned models.

## 👤 Author

**Habimana Enock**  
Data Analyst | Data Science Professional  
[LinkedIn](https://www.linkedin.com/in/enockh) | habimanaenock15@gmail.com


