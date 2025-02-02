NEET AI Performance Analyzer
Video Demonstration: https://www.loom.com/share/edef9d24870444fda3afce63c4068dec?sid=c81ff214-fcc7-4536-b07a-3de9408aaac1
Overview
The NEET AI Performance Analyzer is a Python-based GUI application that analyzes a student's performance in NEET preparation quizzes. It fetches quiz data from APIs, evaluates the student's strengths and weaknesses, predicts their NEET rank, and provides AI-generated study recommendations.
Features
•	Performance Analysis: Analyzes quiz results to determine accuracy and weak topics.
•	NEET Rank Prediction: Estimates the student's rank based on quiz scores.
•	Personalized AI Recommendations: Provides study suggestions tailored to the student's performance.
•	Student Persona Analysis: Identifies strong and weak areas with motivational feedback.
•	Modern GUI: Uses CustomTkinter for a sleek, user-friendly interface with a dark theme.
•	Adjustable Textbox: Scrollable and resizable results display with enhanced readability.
Installation
Prerequisites
Ensure you have Python installed (>= 3.7) along with the required libraries.
Required Python Libraries
Run the following command to install dependencies:
pip install requests openai customtkinter
API Configuration
Replace the openai.api_key in the script with your actual OpenAI API key:
openai.api_key = "your-api-key"
Usage
1.	Run the script: 
2.	python script.py
3.	Click "Analyze Performance" to fetch quiz data and get AI-generated insights.
4.	View Results: 
o	Student Persona: Strengths, weaknesses, and motivation.
o	Predicted NEET Rank: Estimated based on quiz performance.
o	Study Recommendations: Topic-specific suggestions for improvement.
Code Breakdown
1. Data Fetching
The script retrieves quiz data from APIs using the fetch_data() function.
2. Performance Analysis
The analyze_performance() function evaluates quiz accuracy and topic-wise performance.
3. NEET Rank Prediction
The predict_neet_rank() function estimates the student's rank using statistical modeling.
4. AI-Generated Recommendations
The generate_recommendations() function uses OpenAI's GPT-4 model to suggest study plans.
5. GUI Implementation
•	CustomTkinter is used for an elegant dark-themed interface.
•	ScrolledText provides an adjustable text area for displaying results.
•	Formatted output includes bold text and colored highlights for key insights.
Future Enhancements
•	Graphical Analysis: Add charts for better visualization of performance.
•	Export Feature: Save recommendations as a PDF or CSV.
•	Real-time Quiz Integration: Connect with live quizzes for dynamic analysis.






THANK YOU
