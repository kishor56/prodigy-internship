#Task 1 Caesar Cipher Program

This Python program implements the Caesar Cipher algorithm, allowing users to encrypt and decrypt text by shifting the characters in the message. The program is designed to be user-friendly, with prompts guiding the user through the encryption and decryption process.

Features

Encryption and Decryption: The program can both encrypt and decrypt messages using a specified shift value.
User Input: Users can enter their own message and choose the shift value for the cipher.
Usage

Run the Program: Execute the script to start the Caesar Cipher program.
Select Action: Choose 'e' for encryption or 'd' for decryption.
Enter Message: Input the message you wish to process.
Specify Shift: Enter the shift value for the Caesar Cipher.
View Result: The program displays the encrypted or decrypted message.
This code was developed as part of my internship at The Prodigy Infotech, demonstrating basic encryption and decryption techniques using the Caesar Cipher.

#Task 2 Image Encryption Tool

This Python program implements a simple image encryption tool using pixel manipulation techniques. The program can encrypt and decrypt images by performing basic mathematical operations on the pixel values. It is designed to be user-friendly, guiding users through the encryption and decryption processes with clear prompts.

Features

Image Encryption: Users can encrypt an image by applying a mathematical operation to each pixel value, effectively altering the image.
Image Decryption: The program can reverse the encryption process to restore the original image.
User Input: Users can specify the image file and the encryption key.
File Handling: The program saves the encrypted and decrypted images to specified file paths.
How It Works

Encrypt Image: Multiplies each pixel value by a key and then divides by the key plus one to create the encrypted image.
Decrypt Image: Reverses the encryption process by multiplying each pixel value by the key plus one and then dividing by the key.
Usage

Run the Program: Execute the script to start the Image Encryption program.
Select Action: Choose 'e' for encryption, 'd' for decryption, or 'q' to quit.
Encrypt Image:
Enter the encryption key.
Specify the location or URL of the image to be encrypted.
Decrypt Image:
Enter the decryption key.
Specify the location of the encrypted image.
View Results: The program saves and indicates the location of the encrypted and decrypted images.
This code was developed as part of my internship at The Prodigy Infotech, showcasing a basic approach to image encryption and decryption through pixel manipulation.

#Task 3 Password Complexity Checker

This Python program evaluates the strength of a password based on several criteria, offering users feedback on how secure their passwords are. The tool provides tips for creating strong passwords and ensures that users understand the importance of various password components.

Features

Password Strength Assessment: The tool checks for length, presence of uppercase and lowercase letters, numbers, and special characters in the password.
Feedback on Password Strength: Users receive a message indicating whether their password is very strong, strong, moderate, or weak.
Password Masking: For privacy, the tool masks the password input before displaying it.
Security Tips: The program provides tips for creating secure passwords and maintaining good password hygiene.
Usage

Run the Program: Execute the script to start the Password Complexity Checking Tool.
Read Tips: Review the provided tips for creating a secure password.
Enter Password: Input the password you wish to check.
View Feedback: The program will display the masked password and provide feedback on its strength.
This code was developed as part of my internship at The Prodigy Infotech, demonstrating a practical approach to assessing password strength and educating users on creating secure passwords.

#Task 4 Simple Keylogger

This Python program implements a basic keylogger that records and logs keystrokes. It captures the keys pressed by the user and saves them to a log file, providing an educational tool for understanding how keylogging works. This program includes ethical considerations and requires user consent before running.

Features

Key Logging: Records and logs every keystroke along with a timestamp.
Log File: Saves the logged keystrokes to a specified file.
User Consent: Includes a disclaimer and requires user acceptance of terms and conditions.
Duration Control: Allows the user to specify the duration for which the keystrokes should be logged.
Usage

Run the Program: Execute the script to start the keylogger program.
Read and Accept Disclaimer: Carefully read the disclaimer and accept the terms and conditions to proceed.
Specify Duration: Enter the duration in seconds for which the keylogger should run.
Logging Keystrokes: The program will capture and log keystrokes during the specified period.
Review Log: After the duration ends, the log file containing the keystrokes will be saved and its location displayed.
This code was developed as part of my internship at The Prodigy Infotech, demonstrating the creation of a basic keylogger for educational purposes while emphasizing ethical usage and user consent.

#Task 5 Network Packet Analyzer

This Python program is a basic packet sniffer tool that captures and analyzes network packets. It extracts and displays relevant information such as source and destination IP addresses, ports, protocols, and payload data. The tool is designed for educational purposes, emphasizing ethical use and requiring user consent before operation.

Features

Packet Sniffing: Captures TCP network packets in real-time.
Detailed Analysis: Extracts and displays key information from each packet, including:
Source and Destination IP addresses
Source and Destination Ports
Protocol
Payload data (first 50 characters)
Output Logging: Saves the captured packet details to a text file for later review.
Ethical Use Disclaimer: Includes a disclaimer outlining the ethical use of the tool and requires user acceptance of terms and conditions.
Usage

Run the Program: Execute the script to start the packet sniffer tool.
Read and Accept Disclaimer: Carefully read the disclaimer and accept the terms and conditions to proceed.
Packet Capture and Analysis: The program will capture and analyze TCP packets on the network.
Review Log: After the specified number of packets are captured, the details are saved to a text file named packet_sniffer_results.txt.
This code was developed as part of my internship at The Prodigy Infotech, demonstrating the creation of a network packet analyzer for educational purposes.
