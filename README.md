# final-project
This is my final project for CSC 101

im adding some additional changes now

from client import User_Inputs, __Responses

UserInput = ""
ChatBot_Name = "Millan"

print("Welcome To The Medical Chatbot")
print("How May I Assist You Today?")
print("Finding a Diagnosis? Vital Sign Ranges? Or How To Do Vital Signs?")

responses = {"finding a diagnosis": "Type Symptom:", "vital sign ranges": "Temperature, Pulse, or Respirations?", 'how to do vital signs' : 'Temperature, Pulse, or Respirations?',}
responses2 = { "temperature" : "Temperature: 98.6 is the normal temp"}
#split string
#response2 = {"Temperature" : "Normal Range: 12-20 respirations"}


userinput = input()
if userinput in responses.keys():
  print(responses[userinput])
else:
  print("? i don't understand")
if userinput in responses2.keys():
  print(responses2[userinput])
else:
  print('i dont know what you are saying')

#Check = ["finding a diagnosis", "vital sign ranges", "how to do vital signs"]
#Respond = ["Type Symptoms: ", "Which Vitals? Temperature, Pulse, or  Respirations?"]
#if UserInput in User_Inputs:
  #index = User_Inputs.index(UserInput)
  #print("Type Symptoms:" + __Responses)

UserInput = str.lower(input(": "))
