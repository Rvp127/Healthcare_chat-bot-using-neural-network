# Healthcare_chat-bot-using-neural-network
1. This code is for understanding how a healthcare chatbot works while being provided with symptoms from the user
2. This also gives a conversational interaction between the user and the bot
3. Creating a customised dataset in the form of a json file containing the conversation between the Health Care Chat-bot and the Patient as “patterns” and 
   “responses” through tags
4. Each tag has a “pattern” as training data which gives a relevant “response” that is structured in the json file
5. Tokenising the sentences to be broken down to individual words which are stored in empty lists and Lemmatising the words typed by the patient to see if it 
   matches the root word present in the list
6. Representing the words as 0 or 1 depending on occurrence by using Bag-of-words, as the Neural Network model understands mathematical vectors
7. Building the Neural network by specifying Activation function and number of neuron’s for Dense layer along with usage of dropout to prevent overfitting of 
   nodes of neuron’s 
8. Building the Chatbot by using 4 different functions where, the 1st function tokenises the sentence and lemmatise the words, the 2nd function is for Bag-of- 
   words where the sentence is converted into a list full of 0 & 1 indicating whether the word is there or not, the 3rd function predicts the previous 2 
   functions, and the 4th function is to get the responses from the bot 
9. Chatbot provides interactive messages to the user/patient to diagnose and provide basic details about the disease
**10**. To follow the code refer the python file and to understand the methodology please read the project report
**11**. *NOTE* the important part of this code is the 'intents.json' file which is the main reason the bot responds to the users demands. The indentation mentioned in the json file is important to follow as it suits the way how the code works
Hope this gives some understanding on how chatbots work with neural networks...THANK YOU! 
