# Codealpha_BasicChatbot
#It is a simple rule-based chatbot 

# Condition: function used
def basic_chatbot():
    print("=== Basic Chatbot ===")
    print("Talk to me! Type 'bye' to exit\n")
    
    # Condition: loops used
    while True:
        # Condition: input/output used
        user_input = input("You: ").lower()
        
        # Condition: if-elif used for rules
        # Condition: Predefined reply "Hi!"
        if user_input == "hello":
            print("Bot: Hi!")
            
        # Condition: Predefined reply "I'm fine, thanks!"
        elif user_input == "how are you":
            print("Bot: I'm fine, thanks!")
            
        # Condition: Predefined reply "Goodbye!"
        elif user_input == "bye":
            print("Bot: Goodbye!")
            break  # Exit loop
            
        else:
            print("Bot: I only understand 'hello', 'how are you', 'bye'")

# Function call 
basic_chatbot()
