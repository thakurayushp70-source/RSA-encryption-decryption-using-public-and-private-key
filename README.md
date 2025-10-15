
BABU BANARASI DAS UNIVERSITY

 <img width="427" height="419" alt="Screenshot 2025-10-13 222542" src="https://github.com/user-attachments/assets/2d7c4268-67a5-4054-8811-e8f814248c1e" />

SCHOOL OF COMPUTER APPLICATION

Department of Computer Science & Engineering

PRIVACY AND SECURITY IN IOT LAB 
(ITBC3751)
Session 2025-26

PRACTICAL LAB FILE 


SUBMITTED BY :-   

NAME – 

Aachal Gupta  ( 1250264001)

Prashant Singh  (1250264063)

Anku Singh   (1250264018)

Anshuman Singh  (1250264021)

Ayush pratap singh   (1250264034)

                                                                                                                             
SECTION – BCACS11



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

## Project 3 (By Anku Singh)

What Is OpenStego and Steganography?
Steganography is the practice of concealing information within another file or medium to
prevent detection. Unlike cryptography, which scrambles data, steganography hides its very
existence.

OpenStego is a free, open-source tool designed for digital steganography. It allows users to:
Hide data within image files (e.g., embedding a secret message in a JPEG).
Watermark files with invisible signatures to detect unauthorized copying
Learning Outcomes

By using OpenStego, learners and practitioners can:
Understand the principles of steganography and how it differs from encryption.
Gain hands-on experience with hiding and extracting data from image files.
Explore digital watermarking as a method of copyright protection.
Evaluate the security and limitations of steganographic techniques.

Apply ethical hacking skills in cybersecurity labs or forensic investigations.
• Tool/Resource Purpose
• OpenStego software Main application for data hiding and watermarking (Download here)
• Cover file (e.g., image) The file that will conceal the hidden data
• Message file (e.g., text) The secret data to be embedded
• Java Runtime
Environment (JRE) Required to run OpenStego on most systems
• Computer with GUI OpenStego has a graphical interface for ease of use

1. Download and Install OpenStegoVisit openstego.com and
download the latest version.Install it on your system (requires Java
Runtime Environment).


![833228c4-6e89-43a6-b1df-387241c6faa8](https://github.com/user-attachments/assets/bcf6736c-9d2f-4491-b171-dea0b00d13ba)

2. Prepare Your FilesCover File: Choose an image (e.g., .png, .jpg)
that will hide your message.Message File: Create a text file (.txt) with the secret message or data you want to embed.

![5d57d831-99f5-4a95-a205-79dfa1e72eab](https://github.com/user-attachments/assets/d86ae839-3d1e-4e91-b7bd-898723d800ca)


3, Launch OpenStego
Open the application. You’ll see two main tabs: Data Hiding and
Watermarking.

4. Select “Data Hiding” Tab
This mode allows you to embed secret data inside an image.


![62786fa2-66e7-450c-8c2c-7d2e41cb5cc3](https://github.com/user-attachments/assets/7bd3d92c-7e64-48c2-8d58-a90f1d0f2545)

 
5. Choose Your Files
Input Cover File: Browse and select the image file.
Message File: Browse and select the text file containing your secret
message.

Output Stego File: Choose a name and location for the new image that will
contain the hidden data.

6. Set Password (Optional)
You can set a password to encrypt the hidden data for added security.

7. Click “Hide Data”
OpenStego will process the files and generate a new image with the
embedded message.

![af6b8223-71be-48c7-8acc-1cfa03d0fcc7](https://github.com/user-attachments/assets/ebebd221-6c3f-42eb-b390-7a182bac41a3)


8. Verify or Extract Data
To retrieve the hidden message, use the Extract Data option in the same tab.
Provide the stego image and password (if used), and OpenStego will recover
the original message file.




## Project-4 (By Anushuman Singh)
HIDE THE PDF BY IMAGE

1. Launch OpenStego. Find and run the applicaƟon's .jar file. You will see a window
with two main funcƟons: "Hide Data" and "Extract Data".

2. Select "Hide Data". On the main screen, click the "Hide Data" buƩon.
   
3. Choose the message file. Click the "..." buƩon next to the Message File field and
select your PDF file from your computer.

4. Choose the cover file. Click the "..." buƩon next to the Cover File field and select
an image file (such as a .png or .bmp) to serve as the container for your PDF. The
cover file must be larger than your PDF.

5. Specify the output file. Click the "..." buƩon next to the Output Stego File field.
Navigate to the desired save locaƟon and enter a name for the new stego-image
file, including the image extension (e.g., secret_image.png). 

6. Add a password (opƟonal but recommended). For enhanced security, use
the Password and Confirm Password fields to set a password for the hidden PDF.
You can also select an encrypƟon algorithm, such as AES, from
the OpƟons secƟon.

7. Embed the PDF. Click the Hide Data buƩon at the boƩom of the window to
embed the PDF. Open Stego will noƟfy you when the process is complete. 

Part 2 : - Extract the PDF from the image

1. Launch OpenStego. Open the applicaƟon again.
  
2. Select "Extract Data". On the main screen, click the "Extract Data" buƩon.
 
3. Choose the stego file. Click the "..." buƩon next to the Input Stego File field and
select the image file that contains your hidden PDF.

4. Choose the output folder. Click the "..." buƩon next to the Output Folder for
Message File field and select a desƟnaƟon folder where the extracted PDF will be saved.

5. Enter the password. If you set a password during the embedding process, enter it
in the Password field.

6. Extract the PDF. Click the Extract Data buƩon at the boƩom of the window.
OpenStego will extract your PDF file to the specified folder, where you can then
open it normally. 

## Project by-(Ayush pratap singh) 
## Practical 5- Phishing-page
# Phishing-page
Step 1 – Open Kali Linux

Start your Kali Linux operating system, which is a penetration testing Linux distribution preloaded with many cybersecurity tools.

Purpose: Kali Linux provides the right environment for ethical hacking tools like Zphisher.


---

Step 2 – Go to Terminal

Click on the Terminal icon or press Ctrl + Alt + T to open the command-line interface.

 Purpose: The terminal is where you’ll type and execute all Linux commands for installation and running of Zphisher.

![WhatsApp Image 2025-10-14 at 12 06 14 PM](https://github.com/user-attachments/assets/c774192c-3e00-4d0a-ba24-a50e875533b3)

---

Step 3 – Git Clone

Type the following command:

git clone https://github.com/htr-tech/zphisher.git

 Purpose:
This command downloads (clones) the Zphisher repository from GitHub into your local machine.
After completion, a new folder named zphisher will be created in your current directory.


---

Step 4 – Type ls

ls

Purpose:
ls lists all the files and folders in your current directory. You should now see a folder named zphisher among them, confirming successful download.

![WhatsApp Image 2025-10-14 at 12 06 14 PM](https://github.com/user-attachments/assets/07680df8-0b18-4294-b7d7-b460d4639b3d)

---

Step 5 – Change Directory to Zphisher

cd zphisher

 Purpose:
This command moves you inside the zphisher folder, where all tool files are stored.
Now you’re in the correct working directory to run the tool.

![WhatsApp Image 2025-10-14 at 12 06 14 PM (1)](https://github.com/user-attachments/assets/be99e76b-7eb3-4e70-93a9-41209ef8ee10)

---

Step 6 – Run the Zphisher Script

bash zphisher.sh

 Purpose:
This runs the main Zphisher script, launching the tool. You’ll now see a menu interface in your terminal where you can choose options for phishing page setup.
![WhatsApp Image 2025-10-14 at 12 06 14 PM (2)](https://github.com/user-attachments/assets/94d950db-b787-488a-abc6-8dd4d645b6aa)


---

Step 7 – Select Any Social Media (e.g., Instagram)

Zphisher will show a list of popular platforms like:

Instagram

Facebook

Gmail

Twitter
and others.


Select your desired one (e.g., Instagram) by typing its number.

 Purpose:
This selects the target website you want to simulate for the phishing demonstration.
![WhatsApp Image 2025-10-14 at 12 06 14 PM (3)](https://github.com/user-attachments/assets/58bc3583-7f85-4d1c-b437-b4d927be85e7)


---

Step 8 – Select Traditional Login Page

Choose the “Traditional Login Page” option when asked.

 Purpose:
This will use a simple login clone page that looks identical to the official site but is used here for learning how phishing templates are structured.

![WhatsApp Image 2025-10-14 at 12 06 14 PM (4)](https://github.com/user-attachments/assets/793cb86e-ce70-4c89-9ce0-fd305266abf6)

---

Step 9 – Select Localhost

Choose “Localhost” when asked how to host the phishing page.

 Purpose:
This means your phishing page will be hosted locally on your computer, not online — safe for practice because no one else can access it.


---

Step 10 – Get the Link

After setup, Zphisher will generate a localhost link (something like http://127.0.0.1:8080).

 Purpose:
This link opens your phishing simulation page locally.

![WhatsApp Image 2025-10-14 at 12 06 14 PM (5)](https://github.com/user-attachments/assets/1a7d8973-3c10-4ff0-8cdf-7f8adccadc56)

---

Step 11 – Open the Link in Browser

Copy the generated link and paste it into your browser (e.g., Firefox or Chrome inside Kali).

 Purpose:
You’ll see the fake login page (for example, Instagram’s login page copy) loaded locally.
This demonstrates how phishing pages appear to users.
![WhatsApp Image 2025-10-14 at 12 06 14 PM (6)](https://github.com/user-attachments/assets/6f45b5aa-34db-416f-8d0b-bb06ec38d862)


---

Step 12 – Check Details in Terminal

When you (or a test user) enter credentials on that page, the details appear in the terminal window.

 Purpose:
This shows how phishing captures credentials, helping you understand how attackers steal data — and thus, how to prevent it.

![WhatsApp Image 2025-10-14 at 12 06 14 PM (7)](https://github.com/user-attachments/assets/40d9c06c-7694-456b-af5f-8b6294772486)

---

Step 13 – Stop the Program

Press:

Ctrl + C

 Purpose:
This stops Zphisher and ends the local server. Always close it after your testing session.
![WhatsApp Image 2025-10-14 at 12 06 14 PM (8)](https://github.com/user-attachments/assets/8ef08a56-7490-44cf-979c-e8dbdcd263b3)
