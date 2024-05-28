# Task-management-app
The Task Management App is a command-line application designed to help you organize, manage, and prioritize your tasks efficiently. Developed using Python, this app leverages machine learning to provide intelligent task recommendations based on the descriptions and priorities of your tasks.

Key Features

Add Tasks: Easily add new tasks to your list by providing a description and assigning a priority level (Low, Medium, or High).
Remove Tasks: Remove tasks from your list by specifying the task description, keeping your task list up-to-date.
List Tasks: Display all your tasks in a structured format, showing both the task descriptions and their respective priorities.
Task Recommendations: Receive smart task recommendations based on the priority and content of your existing tasks, helping you focus on what matters most.
Data Persistence: Tasks are stored in a CSV file (tasks.csv), ensuring that your task list is saved between sessions and can be easily accessed and managed.

Machine Learning Integration

The app uses the scikit-learn library to create a simple yet effective machine learning model. By analyzing the descriptions and priorities of your tasks, the model can recommend high-priority tasks for you to focus on. This is achieved through a pipeline combining CountVectorizer for text feature extraction and MultinomialNB (Naive Bayes) for classification.
This app is ideal for users who want a simple, command-line tool to manage their daily tasks, enhanced by the power of machine learning to provide useful task recommendations.
