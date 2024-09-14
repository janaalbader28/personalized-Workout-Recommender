# personalized-Workout-Recommender
 personalized workout recommender system based on user input. Users describe their day and select a time of day (morning, afternoon, evening). Based on their mood and the time, the system suggests suitable workouts. The project uses Hugging Face’s sentiment analysis to classify the input text and a DataFrame to store possible workout suggestions

---
#Main Files and Their Functions
Workout-Recommender-Application.ipynb:
Mood Classifier: The SamLowe/roberta-base-go_emotions model is used to identify the user’s mood from their input.
Gradio Interface: This interface allows users to enter their mood and select the time of day, and then it shows a workout suggestion based on this information.

Pipeline-file.ipynb:
Focuses on using Hugging Face pipelines for mood classification and managing the data.

Gradio-file.ipynb:
Focuses on building the Gradio interface.
