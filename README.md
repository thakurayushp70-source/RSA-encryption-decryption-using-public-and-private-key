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
 Verify that the decrypted message is the same as the original message entered in Step 3.
<img width="670" height="402" alt="image" src="https://github.com/user-attachments/assets/c56320c0-b1a1-431f-ae99-cfe26bde7fe8"/>
and decrypted the ciphertext back to the original message using the Private Key.
