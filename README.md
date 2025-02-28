# CODSOFT
Task-1:CHATBOT WITH RULE-BASED RESPONSES

Here's a more detailed summary of my simple chatbot:
**
Imports:**
The datetime module is imported for date and time functions.

Chatbot Response Function:
Converts user input to lowercase for consistent handling.
Uses conditional statements to respond based on specific keywords in the user's input:
Greets with "Hello" or "Hi" and asks for the user's name.
Provides the current time using datetime.now().strftime().
Provides the current date using datetime.today().strftime().
Extracts and uses the name if the input contains "my name is."
Introduces itself if asked, "What is your name?"
Ends the conversation with "Goodbye" or "Bye."
Asks the user to rephrase if the input doesn't match any predefined conditions.

Main Loop:
Continuously runs until the user types "bye."
Prompts the user for input and prints the chatbot's response based on the chatbot_response function.
