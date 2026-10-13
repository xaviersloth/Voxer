# Voxer
Voxer is a chat platform based on Scratch3. Built in Turbowarp, it uses cloud variables to send and receive messages.


Voxer converts the message into numbers 
on the sent variable to the cloud, then the receiver decodes the numbers back into text.


For example, the text "Hello World" is turned into "3405121215854915181204". 

The main reason for this approach is the inability for Scratch servers to store anything but plain numbers and in order to fit all of the characters on a standard keyboard, every character has a 2 number long unique ID. 

Eg. The letter "a" is labelled as "01".


### Note:
The code is extremely bad right now, and I plan a proper rewrite in the near possible future. Some code choices relied on the basis of supporting the original Scratch3 format and with it not being case-sensitive.
