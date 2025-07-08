def chatbot():
    print("Chatbot: Hello! I'm a simple chatbot. Type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower()

        if "hello" in user_input or "hi" in user_input:
            print("Chatbot: Hi there! How can I help you?")
        
        elif "how are you" in user_input:
            print("Chatbot: I'm just a bot, but I'm doing fine. Thanks for asking!")

        elif "your name" in user_input:
            print("Chatbot: I'm RuleBot, your friendly chatbot.")

        elif "help" in user_input:
            print("Chatbot: I can help you with basic queries like greetings, my name, or how I feel.")

        elif "bye" in user_input:
            print("Chatbot: Goodbye! Have a great day.")
            break
        
        else:
            print("Chatbot: Sorry, I didn't understand that. Try something else.")

chatbot()
