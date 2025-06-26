# generative-text-model
summer internship
COMPANY:codetech it solutions
NAME:Medamanoori navya
DOMAIN:Artificial intellegence
INTERN ID:CT04DF1721
DURATION:4weeks
MENTOR:Neela santhosh
DESCRITION:
In this task, we created a basic text generator using Python. The program asks the user for some text and then generates more text based on that input.
We used a simple LSTM model from PyTorch to do the text generation. The user’s input and the generated text are saved in a CSV file.
Module Descriptions 
1. main.py – Main Program
•	Takes user input.
•	Loads the model and generates text.
•	Logs both input and output.
2. model_loader.py – Model Definition
•	Defines a simple LSTM-based model.
•	load_model() returns the model with given parameters.
3. text_generator.py – Text Generator
•	generate_text() produces output from user prompt.
•	Uses softmax sampling for character prediction.
4. logger.py – Input/Output Logger
•	Saves user prompt and model output to a CSV.
•	Adds each as a separate row labeled by type.
5. logs.csv – Interaction Log
•	Stores "Prompt" and "Generated_Text" entries.
•	Automatically updated after each generation.

output:


