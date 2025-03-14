# Cyber Security Projects

### PROJECT 1 - Password Generator Using Python 

#### Description:
A Password Generator helps users generate strong, secure passwords to enhance their cybersecurity practices. This project uses Python to create a script that generates random passwords with customizable length and complexity. The password generator can include lowercase letters, uppercase letters, digits, and special characters to ensure robust password strength.

#### Key Features:
**Customizable Length:** Users can specify the length of the password.
**Password Complexity:** Users can choose to include lowercase, uppercase, digits, and special characters.
**Strong Randomization:** The password is generated using Python’s secrets library to ensure cryptographically secure randomness.
**Password Strength:** The generated password meets common password complexity standards.

#### Technologies Used:
* Python (using secrets for secure randomization)
* Jupyter Notebook (to interactively test and visualize the password generation).

#### Cybersecurity Significance: 
This project ensures that users generate strong passwords, which are a critical part of securing online accounts and systems. The randomness and complexity of the password help mitigate brute-force and dictionary attacks.

***
### PROJECT 2 - Password Manager Using Python 

##### Description:
A Password Manager securely stores, retrieves, and manages passwords using encryption. This project allows users to store multiple passwords in an encrypted file or database and retrieve them securely when needed. It helps mitigate the risks associated with reusing passwords and storing them insecurely.

#### Key Features:
**Secure Storage:** Passwords are stored in an encrypted format using cryptographic algorithms (e.g., AES).
**Password Generation:** Integrates the password generator to help users create strong passwords.
**Password Retrieval:** Allows users to retrieve passwords securely using a master password.
**Encryption/Decryption:** Uses Python libraries like cryptography to encrypt and decrypt passwords.

#### Technologies Used:
Python (using cryptography for encryption and decryption)
Jupyter Notebook (to interactively manage and visualize the password manager).

#### Cybersecurity Significance: 
A password manager improves security by ensuring passwords are not stored in plain text, thus reducing the risk of exposure during a breach. It also encourages using strong, unique passwords for each account.

***
### PROJECT 3 - Web Scraping for Security Monitoring Using Python 

#### Description:
Web scraping can be used to monitor and track publicly exposed sensitive information like passwords, email addresses, or security vulnerabilities. This project demonstrates how to scrape websites to find potentially exposed data or security risks and uses Python to extract and analyze that information.

#### Key Features:
**Scraping Websites:** Extracts publicly available information from websites that might be of concern, such as exposed passwords or sensitive data.
**Monitoring:** Monitors and tracks potentially dangerous data that may have been exposed on the web.
**Alert System:** Alerts the user when sensitive data is found, helping mitigate risks.
**Data Extraction:** Extracts emails, passwords, or other sensitive data from websites that could indicate security vulnerabilities.

#### Technologies Used:
Python (using requests and BeautifulSoup for scraping)
Jupyter Notebook (for easy iteration and data visualization)
Regular Expressions (for identifying patterns like emails, phone numbers, or passwords).

#### Cybersecurity Significance: 
Web scraping can help cybersecurity professionals monitor websites for exposed credentials, emails, and other sensitive data, which could indicate a breach. By identifying exposed information, organizations can respond quickly to minimize risk and protect sensitive data.

***
### PROJECT 4 - Caesar Cipher Encryption

#### Description:
This project implements a simple Caesar cipher encryption algorithm in Python. The Caesar cipher is a basic encryption technique that shifts each letter in a string by a fixed number of positions in the alphabet.

#### Features
- Encrypts a given plaintext using a specified shift value.
- Handles both uppercase and lowercase letters.
- Maintains non-alphabet characters without modification.

#### How It Works
1. The user inputs a plaintext message.
2. The user specifies a shift value (number of positions each letter is shifted).
3. The program encrypts the message and displays the encrypted text.

#### Technologies Used
Jupyter Notebook used for writing and running the Python script interactively.
String Manipulation Used to shift characters in the alphabet for encryption.

#### Cybersecurity Significance
The Caesar cipher is one of the earliest known encryption techniques and serves as a fundamental concept in cybersecurity. While it is not secure by modern standards, it is useful for understanding basic encryption principles.  

