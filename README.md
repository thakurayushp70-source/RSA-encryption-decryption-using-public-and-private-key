
BABU BANARASI DAS UNIVERSITY

 <img width="427" height="419" alt="Screenshot 2025-10-13 222542" src="https://github.com/user-attachments/assets/2d7c4268-67a5-4054-8811-e8f814248c1e" />

SCHOOL OF ENGINEERING 

Department of Computer Science & Engineering

PRIVACY AND SECURITY IN IOT LAB 
(ITBC3751)
Session 2025-26

PRACTICAL LAB FILE 


SUBMITTED BY :-   

NAME – 

Aachal Gupta

Prashant Singh

Anku Singh 
                                                                                                                             
SECTION – BCACS11

ROLL NO -

1250264110

1250264035

1250264018


INDEX


1.	RSA encryption decryption using public and private key.		
2.	Phishing / Spoofing		
3.	Steganography using cmd		
4.	Open Stego		
5.	Nmap configuration
   


## Project-1 (By Aachal Gupta)
USING CMD SEND SECRET MESSAGE

Definition:
This method involves embedding or appending a hidden text message inside an image file using the Windows Command Prompt. The image remains viewable normally, but when opened with a text editor (like Notepad), the hidden message becomes visible at the end of the file’s binary data. This is a simple form of steganography — the practice of hiding information within other files.

Learning Outcomes:
After completing this activity, the learner will be able to:
1.	Understand the concept of file concatenation and steganography.
2.	Use basic CMD commands like echo and type to manipulate files.
3.	Embed and retrieve hidden messages in image files using the command line.
4.	Recognize how data can be stored or concealed within media files.
5.	Develop awareness of information hiding and data security concepts.

Required Tools:
1.	Operating System: Windows (any version supporting CMD).
2.	Command Prompt (CMD): Built-in terminal for executing commands.
3.	A Text Editor: Notepad (to view hidden message).
4.	Image File: Any .png or .jpg file.

Working:
Step-1 Create a folder

<img width="285" height="193" alt="1" src="https://github.com/user-attachments/assets/7a11ed53-1908-45df-956b-289686faef1a" />










Step-2 Insert image in folder in which secret message we want to hide and send it to receiver.


![a2f214f4-2f0c-4cec-8b66-1ada15d0f1cb](https://github.com/user-attachments/assets/af066a5c-9fdb-4dab-a847-36c6da82cf04)



Step-3 Open the folder in terminal.


![e5c6c4b1-0bcd-436f-b75e-9c773028f83f](https://github.com/user-attachments/assets/a0a1b084-8eea-4075-ac07-c73616026cf7)




Step-4 Write ls to see the image in folder, then write the echo “The secret message ” >> image.png (The name of image with extension ), then press enter.


![f0425cd4-2c00-4e45-8d85-9529d6d3389d](https://github.com/user-attachments/assets/a4eea7ae-4b3b-4d3c-a261-b51710a687e7)



Step-5 Now open the image the notepad and scroll all the way down to see the secret message written there.  


![96481c16-2e95-4135-b7e9-531c0d847ab2](https://github.com/user-attachments/assets/341dad34-430d-4947-9c79-4f0844cf48e1)





## Project-2 (By Prashant Singh)
RSA Encryption and Decryption 


Definition:

RSA (Rivest–Shamir–Adleman) is one of the most widely used asymmetric cryptographic algorithms. It uses two different keys – a Public Key for encryption and a Private Key for decryption. The algorithm ensures secure communication over an insecure channel. Any data encrypted using the public key can only be decrypted using the corresponding private key.
Outcomes/Learning:

By the end of this practical, we will be able to learn:
•	Understand the importance of asymmetric encryption in security.
•	Generate RSA public and private key pairs using an online tool.
•	Encrypt a message using the RSA public key.
•	Decrypt a ciphertext using the RSA private key.
•	Verify that the decrypted message is the same as the original input message.
Required Tools:
•	Laptop/PC with Internet connection
•	Web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, etc.)
•	RSA Encryption/Decryption Tool (https://www.devglan.com/online-tools/rsa-encryption-decryption)
•	A sample text message to test encryption and decryption

Working:

Step 1: Open a web browser on your laptop/PC. In the address bar, type the following URL and press Enter:

![58d3945e-8c90-4dc8-922f-ad3753688ed4](https://github.com/user-attachments/assets/42fe7013-b652-4172-a481-f844b58a1e8c)

This will open the RSA Encryption and Decryption online tool.
 
Step 2: Scroll down to the section 'Generate RSA Key Pair'.
- Click on the button 'Generate RSA Key Pair'.
- The tool will generate a Public Key and a Private Key.
- These keys are required for encryption and decryption.
  
 
![50d21510-a12b-4590-b0e9-d09915e58c01](https://github.com/user-attachments/assets/b7789e7b-32e9-40c2-8c84-74d0efb338d4)

Step 3: Scroll down to the 'Encrypt' section of the tool.
- In the input text box, type a sample message (for example: 'Hello RSA Encryption').
- Now click on the 'Encrypt' button.

   ![210bb2fd-ddc7-4538-964d-bbed0d0a05b1 (2)](https://github.com/user-attachments/assets/6e93fc1e-34c2-4c6a-bbc3-25e8be57c404)


  Step 4: Once you click on Encrypt, the tool will generate an encrypted message, also called the Ciphertext.
- This ciphertext is unreadable and can only be decrypted using the corresponding Private Key.
- Copy this encrypted text.
   
 



![9f74ad56-2241-4291-a252-54163a420eae](https://github.com/user-attachments/assets/444a075f-fc60-481e-bb3a-f61c0999321d)



Step 5: Scroll further down to the 'Decrypt' section of the tool.
- Paste the ciphertext (from Step 4) into the Ciphertext input  box.
- Now click on the 'Decrypt' button.

 
![7bc94d5c-7ce5-4663-b4db-4dd846f1e946](https://github.com/user-attachments/assets/71a4656a-8ee3-4410-88be-f512f3a01581)


Step 6: After clicking on Decrypt, the tool will display the original plain text message.
- Verify that the decrypted message is the same as the original message entered in Step 3.


![4fa04e80-e148-439b-a9d5-3fcf3c12eb25](https://github.com/user-attachments/assets/dd410dfc-261e-4747-88ac-eecf1332adf7)

 
Step 7: Conclusion – Through this practical, we have successfully generated RSA keys, encrypted a sample message using the Public Key, and decrypted the ciphertext back to the original message using the Private Key.

