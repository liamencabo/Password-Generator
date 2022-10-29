# Password--Generator

This project is a Java Console Application to generate Random passwords and performing a password strength check.

I wanted to build upon and be more familir with Java. Over the course of determining what to create I stumbled upon a creating a password generator. Too many times we stumble across creating a password that we have not already used or one that can be easily decrypted. So, what better way to build upon Java than to create a Java Password Generator that generated the password for you! While working on it I decided to include a password <b>strength checker</b> feature that checks for the overall strength of the entered password and I was pretty happy with how it came out but I realised that it was not very straight forward to use for someone who does not know how it is supposed to work so I decided to create a GUI for the application for the next step it is available in the Password-Services repository!

Functionalities:

1- Generating a Password:

The user must answer by Yes or No the questions to know if they desire to use Uppercase/Lowercase letters, Numbers or Symbols
The user then enters the desired length of the password
A password alphabet is generated according to the Yes/No answers it is a String that contains the choices of the user
Depending on the length random characters from the password alphabet are selected and put back to back to form a totally random string according to the user's needs
The randomly generated password is then displayed on the console

2- Checking a Password's Strength:

The Strength check is based on the following criteria:

- The password uses Uppercase Letters
- The password uses Lowercase Letters
- The password uses Numbers
- The password uses Symbols
- The length of the password is 8 or more (8 is often the minimum required length for a decent password)
- The length of the password is 16 or more (16 is considered to be the minimum length for good password)
- These are used to calculate a score for the password used to know what message to display to the user weak/medium/good/great password

3- Displaying Useful Information:

This is a minor feature that displays on the console so information for the user about password security (Avoid using the same password twice/ Avoid character repetition, keyboard patterns, dictionary words, letter or number sequences, etc.)
