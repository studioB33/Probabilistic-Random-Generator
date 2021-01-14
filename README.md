# Probabilistic-Random-Generator
This is a unity project file. This program assigns attributes to objects by reading a text file that contains combinations of these attributes and probabilities.

The scene generates a corridor with 20 doors. Each door has the possiblity of being hot, noisy or safe. The combination of attributes are demonstrated by GUI components. For example, if a door is hot, it will appear red. The program generates doors and reads a text file. 

Text file format:

Hot Noisy Safe  Probability
Y     N     Y       0.3
Y     Y     Y       0.4

The probabilities of all combinations will add up to 1.0. 
That probability determines how many doors out of the total number of doors in the corridor will contain that set of attributes. (total number of doors * probability = number of doors that have the combination of attributes)

Then, it assigns the attributes in a random order to the doors.
