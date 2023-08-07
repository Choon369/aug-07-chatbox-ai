# aug-07-chatbox-ai

// we will use dialog flow to create an ai chatbox 
 *dialogflow provide a nlu platform which be used to create chatbox other services are aws lex ibm watson
architecture
 user --> chatbox --> intent --> entity --> fullfilment(flask app)
             ^------------------------------------------|
 intent is something user want to do( problem to do is hidden in intent )
 entity e.g " convert x usd to inr" here the whole sentence is the intent like convert but word like "usd" and "inr" are entity .
 fullfilment id the fuction to do work
