# Executive Summary
Explain the goal for this lab

The goal of this lab is to help students understand the different types and processes of cybersecurity as well as help students understand how to secure or encrypt their data from hackers looking to intercept it. 
# Cybersecurity and Encryption

* Imagine you are part of the Amazon.com online chat. Explain how each component of the security triad would impact your job

As an amazon chat employee I first have to verify the user's identity to prevent sensitive information from unauthorized access attempts. After confirming the user's identity as the person owning the account, steps must be taken to ensure data cannot be altered by unauthorized people. This involves maintaining the consistency, accuracy and trustworthiness of from the user data or in simpler terms; making sure the user's information has not been altered in any way. Then, I should be confirming with the user whether or not that data is correct. Working as a chat employee I would have to also make sur the user's data is consistently and readily accessible for all authorized parties.

* Identify three daily tasks that require authentication. 
3 tasks that would require some type of authentication would be accessing your credit card account, logiong into a new gmail account, and logging into your bank account to see you statement. 

* Explain how each one could be converted to multi-factor authentication

* A bank account authentification process may could be converted into a 2 step authentification procces by verifying the actie users last 4 digits of the social and confirming the last 4 payments.


* Explain ACL and RBAC. What are the advantages and disadvantages of each?

RBAC (Role based access control) is based on defining a list of business roles, and adding each user in the system to one or more roles. 

Discretionary Access Control (DAC) allows a user or administrator to define an Access Control List (ACL) on a specific resource (e.g. file, registry key, database table, OS object, etc), this List will contain entries (ACE) that define each user that has access to the resource, and what her privileges are for that resouce.

The main benefit of RBAC over DAC, is ease of management - in principle you have a very few roles, centrally administered, no matter how many users, and its just a question of granting each user the correct role; as opposed to DAC, where for each new user (or change in user, or deletion, etc), you have to go around to all the resources she needs access to and add them to the list. On the other hand, DAC is often simpler, and generally more granular. Also, in the DAC model the data owner can decide who has access (if he has that permission on the data) and add or remove people from the list.

* Explain the interaction of ciphertext, a public key and a private key

Cipher is an algorithm which is applied to plain text to get ciphertext. It is the unreadable output of an encryption algorithm. Ciphertext is not understandable until it has been converted into plain text using a key. A public key is used to encrypt the plain text to convert it into cipher text and another key (private key) is used by receiver to decrypt the cipher text to read the message.

* Explain why we need public key cryptography.
 
Public key cryptography remains the most secure protocol (over private key cryptography) because users never need to transmit or reveal their private keys to anyone, which lessens the chances of cyber criminals discovering an individual's secret key during the transmission.

## Cryptography
* Type a message in the "Caesar Cipher Exploration box and turn the wheel to encrypt your message.
Then explain the encryption here: 

I was thinking of what would be a good message to encrypt so I remember when I was watching this Ted Talk of a scientist, and he was talking about the coded message that was found in the human DNA. The code was: Eternal God Within the Body so I figured I would input that and shift it to to 2 because 26 divided by 8 equals 3.25 and 6 dived by 3 would be 2. I used 6 because we are 6 protons, 6 neautrons, and 6 electrons. Therefore, that's how I got the code I got. 

Message: enternal body within the body 
Encryption: fufsobm hpe xjuijo uif cpez

* Type a message in the "Frequency Fingerprint Exploration" box and a) Explain the result.
b) Would it be different for different languages?

I typed in "apollo" but it came out if a way thats difficult to describe. The result filled the red bars of the letter frequencies depending on how many times they were used in the phrase. 
The details and characteristics of the "pattern" or "fingerprint" would be different, but the principle would be the same.

* What is a "Polyalphabetic cipher?"
Type a message in the "Polyalphabetic Exploration" box as well as a shift word.
Explain the result.

I typed in strange fruit; through the polyalphabetic cipher and it came back encrypted as "hhwpblt twjwy"
A polyalphabetic cipher is any cipher based on substitution, using multiple substitution alphabets.

## Brute Force
* What is Brute-Force and how does it relate to Kerckhoffs's principle?
* Kerckhoff's principle allows for the possibility that the entire encrypted message and even the encryption algorithm used to produce it may be intercepted by an attacker or spy, without compromising the overall security of the system.
* A brute force attack uses trial-and-error to guess login info, encryption keys, or find a hidden web page. Hackers work through all possible combinations hoping to guess correctly because the original key is encrypted.

# Conclusion
Summarize how this lab was useful to you and what you learnt that really interested you!

In this lab I learned the different types and processes of cybersecurity as well as how to secure or encrypt data from hackers looking to intercept it. The lab will be utilized later down the line whenever I have sensitive data that needs to be encrypted.
