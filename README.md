# File-Hash-Integrity-Checker

Description:
This Python application, built using the tkinter library, provides a simple yet essential utility for verifying the integrity of any digital file. It calculates the SHA-256 hash of the selected file, a standard cryptographic primitive used to ensure that a file has not been tampered with or corrupted.

This project demonstrates proficiency in:
•	Cryptography Fundamentals: Practical application of secure hashing algorithms (hashlib).
•	System Security: Core concept for security auditing, software distribution, and secure storage in distributed systems.
•	GUI Development: Using tkinter for UI/UX design and user interaction.
•	System I/O: Efficiently handling file streams for both small and large files (reading in chunks).
Requirements are Python 3.x, tkinter (Usually included with standard Python installations) and hashlib.

Working:
•	Click the "Browse" button to open a file dialog and select any file from your system (e.g., an image, document, or executable) or copy your file path.
•	Click "Calculate Hash" to instantly generate the unique 64-character SHA-256 hash.
•	Integrity Check: If the file is modified even by a single byte, rerunning the checker will produce a completely different hash, indicating the file's integrity has been compromised.

Output:
<img width="976" height="496" alt="image" src="https://github.com/user-attachments/assets/ed8ebba8-e22a-492a-9ce2-8aa3e6b0cf49" />
