# final-project
This is my final project for CSC 101

im adding some additional changes now

from client import User_Inputs, __Responses

UserInput = ""
ChatBot_Name = "Millan"

print("Welcome To The Medical Chatbot")
print("What May I Assist You Today?")
print("Finding a Diagnosis? Vital Sign Ranges? Or How To Do Vital Signs?")

#Check = ["finding a diagnosis", "vital sign ranges", "how to do vital signs"]
#Respond = ["Type Symptoms: ", "Which Vitals? Temperature, Pulse, or  Respirations?"]

UserInput = str.lower(input(": "))


if UserInput in User_Inputs:

