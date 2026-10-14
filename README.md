# Voxer
Voxer is a chat platform based on Scratch3. Built in Turbowarp, it uses cloud variables to send and receive messages.


Voxer converts the message into numbers 
on the sent variable to the cloud, then the receiver decodes the numbers back into text.


For example, the text "Hello World" is turned into "3405121215854915181204". 

The main reason for this approach is the inability for Scratch servers to store anything but plain numbers and in order to fit all of the characters on a standard keyboard, every character has a 2 number long unique ID. 

Eg. The letter "a" is labelled as "01".

## How does this work?
The code takes a input, then converts it into numbers for the server to be able to take the message.
For example, a simple message that is just "hi" will be converted into "0809". The client on the other side would then
take that message and read every 2 numbers. Then it would convert it back into text to successfully get the message.

### Case-sensitive hell: 
Due to the nature of how Scratch was created by MIT Media Lab, comparison operators are not case sensitive. Basically, Scratch can't tell the difference between capital A and lowercase A. This is an issue as that would mean that messages couldn't use capital letters which is the most basic function ever. Even the Talkomatic a system from 1973, supported both uppercase and lowercase characters. The way I got it to work was a mix of using costumes to switch to the letter and using that.

### Note:
The code is extremely bad right now, and I plan a proper rewrite in the near possible future. Some code choices relied on the basis of supporting the original Scratch3 format and with it not being case-sensitive. This project is mostly a experiment and coded on a school laptop. This would be hosted on the Scratch platform but they don't allow chatrooms and Scratch is blocked on my school internet ( for some reason ). Also, the image below was from a friend.

<img width="248" height="203" alt="unnamed" src="https://github.com/user-attachments/assets/d2b1360d-1ede-46c3-96e1-d1523c0c34cc" />

