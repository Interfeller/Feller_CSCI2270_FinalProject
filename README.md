# Feller_CSCI2270_FinalProject
I will be working with Paige Arthur and Evan Sidrow on this project. 

Thanks to incredible advances in medical technology, organ donation has saved countless lives. With this
procedure comes a dilemma, however- there are far more patients in need of donations than there are organs
available for donation. This raises the question: who will recieve a donation when it is available? It is 
a difficult problem that must be approached with both logic, and compassion. 

The goal of our project is to create a program that pairs up organ donors to patients in 
need of donations in a way that maximizes the number of lives saved. 

Parameters of the Patients:
1. Organ Needed
2. Blood Type
3. Location
4. Chance of Transplant success
5. Need (timeline)

Parameters of the Donors:
1. Organ Donating
2. Blood type
3. Location

Taking the parameters of the patients, we will develop a list to determine who is most in need of a donation at
a certain point in time. We will also build a graph of all the locations of the recipients and donors, in order to 
determine how much time it would take to move a donation to a patient, and use that information to determine who
recieves this donation. The patients will be sorted by organ needed and blood type, and the queue will be iterated 
through as we enter donor information. 
