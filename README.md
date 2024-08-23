
# Define a dictionary with responses
responses = {
    "hello": "Hi, how are you?",
    "hi": "Hello! What's up?",
    "bye": "Goodbye! See you later!",
    "thanks": "You're welcome!",
    "default": "I didn't understand that.",
    "how are you": "I'm good, thanks!",
    "what is your name": "My name is ChatBot",
    "what can you do": "I can chat with you!",
    "what is your last name": "my last name is bot",
    "what is python": "Python is a high-level, interpreted programming language.",
    "who created python": "Python was created by Guido van Rossum.",
    "what is the print function in python": "The print function in Python is used to output text to the screen.",
    "what is a variable in python": "A variable in Python is a name given to a value.",
    "what is a list in python": "A list in Python is a collection of items that can be of any data type.",
    "what is a dictionary in python": "A dictionary in Python is a collection of key-value pairs.",
    "what is a loop in python": "A loop in Python is used to execute a block of code repeatedly.",
    "what is a conditional statement in python": "A conditional statement in Python is used to execute a block of code if a certain condition is true.",
        "what is the capital of pakistan": "Islamabad",
    "what is the largest city in pakistan": "Karachi",
    "what is the national language of pakistan": "Urdu",
    "what is the national dish of pakistan": "Biryani",
    "who is the founder of pakistan": "Muhammad Ali Jinnah",
    "what is the highest mountain peak in pakistan": "K2",
    "what is the longest river in pakistan": "Indus River",
    "what is the national animal of pakistan": "Markhor",
    "what is the national bird of pakistan": "Chukar Partridge"
    
}


def chatbot():
    print("Welcome to the chatbot!")
    while True:
        user_input = input("You: ").lower()
        response = responses.get(user_input, responses["default"])
        print("Bot:", response)
        if user_input == "bye":
            break
            
chatbot()
