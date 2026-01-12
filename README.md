


I built an AI agent with gemini. Through this the project I learned about the Gemini API and add other things. 

To install 
git clone repository 
pip install requirements.txt
python3 src/main.py "Your Prompt"

*To use Gemini AI you will need to go to https://aistudio.google.com/ to get an API key. You will need to create a .env folder in root and then create GEMINI_API_KEY= "Paste Key Here"


As an example I built a calculator in which I introduced a bug into the code to see if the agent was able to search through the directory and then read and write to the file. 


The Bugged Calculator
class Calculator:
    def __init__(self):
        self.operators = {
            "+": lambda a, b: a + b,
            "-": lambda a, b: a - b,
            "*": lambda a, b: a * b,
            "/": lambda a, b: a / b,
        }
        self.precedence = {
            "+": 3,
            "-": 1,
            "*": 2,
            "/": 2,
        }

