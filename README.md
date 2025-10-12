## definition
RSA (Rivest–Shamir–Adleman) is one of the most widely used asymmetric cryptographic algorithms. It uses two different keys – a Public Key for encryption and a Private Key for decryption. The algorithm ensures secure communication over an insecure channel. Any data encrypted using the public key can only be decrypted using the corresponding private key

## Outcomes/Learning:
By the end of this practical, we will be able to learn:
•	Understand the importance of asymmetric encryption in security.
•	Generate RSA public and private key pairs using an online tool.
•	Encrypt a message using the RSA public key.
•	Decrypt a ciphertext using the RSA private key.
•	Verify that the decrypted message is the same as the original input message.
•	RSA Encryption/Decryption Tool (https://www.devglan.com/online-tools/rsa-encryption-decryption)
•	A sample text message to test encryption and decryption
Working:
- Step 1: Open a web browser on your laptop/PC. In the address bar, type the following URL and press Enter:
https://www.devglan.com/online-tools/rsa-encryption-decryption

This will open the RSA Encryption and Decryption online tool
- Step 2: Scroll down to the section 'Generate RSA Key Pair'.
  Click on the button 'Generate RSA Key Pair'
The tool will generate a Public Key and a Private Key.
  These keys are required for encryption and decryption

<img width="648" height="552" alt="image" src="https://github.com/user-attachments/assets/a1f3b6a6-1923-4784-8717-9adb166b4ed1"/>

- Step 3: Scroll down to the 'Encrypt' section of the tool.
 In the input text box, type a sample message (for example: 'Hello RSA Encryption').
 Now click on the 'Encrypt' button

<img width="576" height="609" alt="image" src="https://github.com/user-attachments/assets/49f6025f-22fb-42ce-b685-af8c6064fc3e"/>

- Step 4: Once you click on Encrypt, the tool will generate an encrypted message, also called the Ciphertext.
 This ciphertext is unreadable and can only be decrypted using the corresponding Private Key.
 Copy this encrypted text

- Step 5: Once you click on Encrypt, the tool will generate an encrypted message, also called the Ciphertext.
 This ciphertext is unreadable and can only be decrypted using the corresponding Private Key.
 Copy this encrypted text

<img width="646" height="473" alt="image" src="https://github.com/user-attachments/assets/496bd9a5-8985-4710-987e-0b74732a7f4e"/>

- Step 6: Scroll further down to the 'Decrypt' section of the tool.
 Paste the ciphertext (from Step 4) into the Ciphertext input  box.
 Now click on the 'Decrypt' button

<img width="576" height="624" alt="image" src="https://github.com/user-attachments/assets/ebe8d3ed-19c8-4b30-bc5f-ca2f68c33264"/>

- Step 7: After clicking on Decrypt, the tool will display the original plain text message.
   Verify that the decrypted message is the same as the original message entered in Step 3

<img width="670" height="402" alt="image" src="https://github.com/user-attachments/assets/c56320c0-b1a1-431f-ae99-cfe26bde7fe8"/>

- and decrypted the ciphertext back to the original message using the Private Key.



### PROJECT 2
## BY AACHAL GUPTA


## BY USING CMD SEND SECRET MESSAGE 

 

## Definition: 

This method involves embedding or appending a hidden text message inside an image file using the Windows Command Prompt. The image remains viewable normally, but when opened with a text editor (like Notepad), the hidden message becomes visible at the end of the file’s binary data. This is a simple form of steganography — the practice of hiding information within other files. 

 

## Learning Outcomes: 

After completing this activity, the learner will be able to: 

Understand the concept of file concatenation and steganography. 

Use basic CMD commands like echo and type to manipulate files. 

Embed and retrieve hidden messages in image files using the command line. 

Recognize how data can be stored or concealed within media files. 

Develop awareness of information hiding and data security concepts. 

 

### Required Tools: 

Operating System: Windows (any version supporting CMD). 

Command Prompt (CMD): Built-in terminal for executing commands. 

A Text Editor: Notepad (to view hidden message). 

Image File: Any .png or .jpg file. 

 

### Working: 

- Step-1 Create a folder 

 ![f2e0b53b-ee7d-40c7-a1bb-0572abfb5ac1](https://github.com/user-attachments/assets/5f639495-ddd9-407a-a572-3e75a13f8277)


- Step-2 Insert image in folder in which secret message we want to hide and send it to receiver. 

 ![68a7c675-e99b-4ce3-bb95-4695f4c212fa](https://github.com/user-attachments/assets/7c0222c2-03ec-4fb6-9c1d-c05c4d198f5d)


- Step-3 Open the folder in terminal. 
![0ccae0c1-da9d-4d7c-9595-0f07844f80c6](https://github.com/user-attachments/assets/8a6ddc93-791e-4271-982c-e0dcfc0ca47f)


- Step-4 Write ls to see the image in folder, then write the echo “The secret message ” >> image.png (The name of image with extension ), then press enter. 

 ![1c420e1a-8bce-4b76-937e-5a8c9f43f914](https://github.com/user-attachments/assets/a9a429db-3022-4f58-a4ce-fc0700e258c8)


 


- Step-5 Now open the image the notepad and scroll all the way down to see the secret message written there.  

 ![1125c90e-1bdd-43b1-96f5-2fcf5b0868af](https://github.com/user-attachments/assets/9303c854-a830-4337-b161-bb939d2061cc)


 

 
