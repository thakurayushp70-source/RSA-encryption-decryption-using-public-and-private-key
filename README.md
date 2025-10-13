
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


