🚀# SpaceX-Landing-Prediction🚀
This project uses machine learning to predict Falcon 9 booster landings based on SpaceX launch data. Key factors include launch site, payload mass, orbit type, and booster reusability. The model achieves 94.4% accuracy, helping improve rocket recovery and cost efficiency.


🚀 SpaceX Falcon 9 Landing Prediction

 Project Overview

This project explores historical SpaceX Falcon 9 launch data to determine if a booster will land successfully. Using machine learning, we analyze key factors like launch site, payload mass, orbit type, and booster reusability to make accurate predictions.

📌 Key Questions Explored
1. What is the overall success rate of Falcon 9 landings?
2. Which launch sites have the highest success rate?
3. Does payload mass affect the success of landings?
4. How has the landing success rate changed over time?
5. Are reused boosters more successful than new ones?
6. Can machine learning predict Falcon 9 landing success?

Goals

Understand Falcon 9 landing success rates in different conditions.

Visualize trends in landing outcomes using data analysis.

Develop a predictive machine learning model to estimate landing success.

Assess model performance and interpret findings for real-world applications.


Tools & Technologies

Python for data analysis & modeling

Pandas, NumPy for data manipulation

Matplotlib, Seaborn for visualization

Scikit-learn for machine learning

Jupyter Notebook for interactive coding


Key Insights from Data Analysis

Success Rate: About 66.7% of Falcon 9 landings are successful.

Best Launch Sites: KSC LC 39A and CCSFS SLC 40 have the highest landing success rates.

Payload Mass Impact: Heavy payloads can land successfully, but failures also occur across different payload sizes.

Improvement Over Time: SpaceX’s landing success rate improved dramatically from 2015 onward, reaching near-perfect rates by 2018-2020.

Reused Boosters Perform Better: Reused boosters have a 72.9% success rate, compared to 52.8% for new ones.


Machine Learning Model

Model: Random Forest Classifier

Features Used: Launch Site, Payload Mass, Orbit, Booster Reusability, GridFins, Legs

Target Outcome: Booster landing success or failure


Model Performance


Accuracy: 94.4%

Precision: 100% (Success), 80% (Failure)

Recall: 93% (Success), 100% (Failure)

F1-Score: 0.96 (Success), 0.89 (Failure)




Future Enhancements

Fine-tune the model to improve accuracy.

Include additional features like weather conditions and launch angles.

Deploy the model as a web app using Flask or Streamlit.


Credits

Data Source: SpaceX launch data from Kaggle/Wikipedia.

Tools Used: Python, Jupyter Notebook, Scikit-learn, Seaborn.
