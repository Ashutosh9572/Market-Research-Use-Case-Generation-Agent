Multi-Agent Market Research and Use Case Generation System

This project is a multi-agent system designed to conduct in-depth market research and generate AI/ML use cases for a target company within a specific industry. Using Google Generative AI, CrewAI, and Streamlit for an interactive user interface, this system enables quick, automated research and report generation through specialized agents.

Project Overview :

This system leverages four main agents to complete distinct tasks:

1.) Research Agent - Gathers industry insights and competitor analysis for the target company.
2.) Use Case Generation Agent - Proposes relevant AI/ML and Generative AI applications based on research findings.
3.) Resource Collection Agent - Identifies suitable datasets from platforms like Kaggle, HuggingFace, and GitHub for suggested use cases.
4.) Report Generation Agent - Compiles all findings into a detailed report ready for decision-making.

Key Features :

1.) Automated Market Research: Collects and analyzes industry and company information.
2.) AI/ML Use Case Recommendations: Generates actionable AI/ML use cases tailored to the industry and company’s goals.
3.) Dataset Search: Locates relevant datasets to support the use cases.
4.) Report Generation: Compiles a comprehensive report, downloadable in plain text format.
5.) Streamlit Interface: Interactive web interface for easy input and real-time feedback.

Technology Stack :

1.) Python: Core programming language.
2.) Streamlit: Web framework for the UI.
3.) CrewAI: Task orchestration and agent management.
4.) Google Generative AI: Provides the underlying generative model.
5.) dotenv: Manages environment variables.
6.) SerperDevTool: Used for Google searches (optional).
7.) Installation

To run this project, follow these steps:

-> Clone this repository to your local machine.
 git clone [https://github.com/ramamoorthy07/Multi-Agent-Market-Research-and-Use-Case-Generation-System.git]

-> Navigate to the project directory.
 cd Multi-Agent-Market-Research-and-Use-Case-Generation-System
 
-> Install the required dependencies.
 pip install -r requirements.txt
 
Set up API keys:

-> Create a .env file in the root directory and add your API keys for Google Gemini Flash 1.5 and SerperAPI as follows: GOOGLE_API_KEY= SERPER_API_KEY= TOGETHER_API_KEY=


Usage :

1.) Ensure you have installed all dependencies as instructed above.

2.) Run the Streamlit app.

streamlit run app.py
Access the app through your browser at http://localhost:8501

Interact with the app:

Enter the name of the company and the relevant industry (e.g.,Tech, Health, Automotive, Finance, Retail). The app will generate a detailed financial and market research report, including AI use cases and relevant datasets.
