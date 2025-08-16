Math Question Generator with Diagram

This project generates mathematics multiple-choice questions with:
Clearly formatted metadata (@title, @description, @question, etc.)
Realistic distractor options with one correct answer

Detailed explanation

An illustrative diagram embedded in the .docx output

Output Example

The generated .docx file includes:
Two sample math questions (Combinatorics & Geometry)
Answer options with the correct one marked using @@option
Step-by-step explanations
Diagram image illustrating the problem

Features

Fallback Mode — Generates predefined, varied questions without needing API access.
LLM Mode (optional) — If OPENAI_API_KEY is set, uses OpenAI API to generate fresh, unique questions each time.
Automatic .docx creation — Output is ready to submit or use in assessments.
Clean, modular code — Easy to extend for more question types.

How to Run
1. Clone the Repository
git clone https://github.com/yasharthrana/math-question-generator-yr.git
cd math-question-generator

2. Create and Activate Virtual Environment
python -m venv venv

On Windows PowerShell:
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\venv\Scripts\activate

3. Install Requirements
pip install -r requirements.txt

4. (Optional) Set OpenAI API Key
$env:OPENAI_API_KEY="sk-your-api-key-here"

5. Run the Script
python main.py

The generated file will be in:
output/questions_output_with_diagram.docx


📌 Notes
If no API key is provided, the program runs in Fallback Mode using predefined question templates.
All outputs follow the required format for the HighScores.ai assignment.