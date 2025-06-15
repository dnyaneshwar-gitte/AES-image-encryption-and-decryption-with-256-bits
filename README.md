🔐 AES Image Encryption and Decryption [256-bit]
📝 Project Overview
This project demonstrates the 256-bit AES (Advanced Encryption Standard) algorithm applied to image files to ensure robust data confidentiality. It serves as a practical implementation of cryptography and network security principles, offering hands-on experience in image encryption/decryption using Python and Kali Linux.

Through this project, users can encrypt any image using a password and later decrypt it using the same key, simulating real-world secure data transmission and storage scenarios.

⚙️ System Requirements
Operating System: Kali Linux (recommended via Oracle VirtualBox to avoid compatibility issues)

Python Version: 3.10.1

📦 Python Libraries Used
NumPy - v1.13.3

Pillow (PIL) - v9.0.0

PyCryptodome - v3.12.0

Tkinter - (Built-in for GUI)

🔄 Workflow
1. 🔍 Image Selection
Choose an image file from your system using a GUI file dialog.

2. 🔑 Password Entry
Enter a custom password that will be used as the encryption key (AES-256 requires a 32-byte key).

🔒 Encryption Process
Once the image and password are provided:

AES-256 encryption is applied to the image.

Time taken depends on image resolution and system resources.

📁 Output Files Generated
Secret Image – The core encrypted image file.

Visual Encryption Image – A watermarked or visually altered version for verification.

2-Share Encryption Images – Optional: Two image shares used for visual cryptography.

project.crypt – Final fully encrypted image file with AES-256.

🔓 Decryption Process
Select the previously encrypted file (project.crypt).

Enter the same password used during encryption.

The image is decrypted and restored to its original format.

🛡️ Key Features
🔐 AES-256 Encryption – Industry-grade symmetric key encryption.

🖼️ Image-based Security – Focused on securing visual data.

🧪 Hands-on Cryptography – Explore how modern data security works.

🖥️ Linux-Based Development – Built and tested on Kali Linux for cybersecurity enthusiasts.

🧠 Educational Tool – Ideal for students learning cryptography, Python, and secure file handling.

📸 Screenshots (Optional)
Add GUI or command-line screenshots here to showcase the encryption and decryption process.

🧑‍💻 Future Enhancements
Support for video encryption.

Multi-user authentication.

AES-GCM for authentication with encryption.

Web or mobile-based interface.

📚 References
AES Standard Documentation (NIST)

PyCryptodome Documentation

👨‍🏫 Author & Credits
This project was developed as part of a Cryptography & Network Security course to demonstrate secure image handling and encryption techniques using Python and AES-256.
