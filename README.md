# Crew-AI-Practice-Projects

This repository contains practice projects using CrewAI framework to create multi-agent systems. The projects demonstrate how to build collaborative AI agents for various tasks like financial analysis and job application assistance.

## Important Update
The code has been updated to use Google's Gemini API instead of OpenAI's GPT, making it freely accessible for all users. This change allows you to run the notebooks without requiring an OpenAI API key.

## Projects Included

1. **Financial Analysis (L6)**
   - Multi-agent collaboration for financial market analysis
   - Includes data analysis, trading strategy development, execution planning, and risk assessment
   - Uses Gemini API for natural language processing

2. **Job Application Assistant (L7)**
   - AI-powered job application optimization
   - Features resume tailoring, interview preparation, and job market research
   - Leverages Gemini API for intelligent processing

## Setup Requirements

1. Install required packages:
```python
pip install crewai==0.28.8 crewai_tools==0.1.6 langchain_community==0.0.29
pip install langchain-google-genai
```

2. Set up your Gemini API key in the utils.py file
3. Set up SerperDev API key for web search functionality

## Note
This is a modified version of the original course projects, adapted to use Gemini API for improved accessibility. The functionality remains the same, but the implementation is more accessible as it uses Google's free API tier.
