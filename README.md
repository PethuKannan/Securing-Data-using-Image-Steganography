# Securing-Data-using-Image-Steganography

## 📌 Project Overview
This project implements **Image Steganography** using Python and OpenCV. It allows users to securely hide and retrieve secret messages inside an image while maintaining its visual integrity. The encryption is further secured with a password-based authentication system.

## 🚀 Features
- 🔒 **Secure Message Embedding:** Hides text inside an image without noticeable changes.
- 🔑 **Password Protection:** Ensures only authorized users can decrypt the hidden message.
- 📷 **Uses Image Pixels:** Encodes text within pixel values, making detection difficult.
- ⚡ **Lightweight & Fast:** Simple implementation with minimal computational overhead.
- 🎯 **Cross-Platform Compatibility:** Works on both Windows and Linux.

## 🛠 Technologies Used
- **Programming Language:** Python 🐍
- **Libraries:** OpenCV (cv2)
- **Encryption Method:** Pixel-based encoding
- **Security:** Password-protected decryption

## 📂 Project Structure
```
│── stego.py             # Main script for encoding & decoding messages
│── messi.jpg           # Example input image (Replace with your own)
│── encryptedImage.jpg  # Output image with hidden message
│── README.md           # Project documentation
```

## 🏗 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/secure-steganography.git
cd secure-steganography
```
### 2️⃣ Install Dependencies
```bash
pip install opencv-python
```
### 3️⃣ Run the Script
```bash
python stego.py
```

## 🖥️ How It Works
1. **Message Encoding:**
   - The script asks for a **secret message** and a **password**.
   - It modifies specific **pixel values** in the image to store the message.
   - The encoded image is saved as `encryptedImage.jpg`.

2. **Message Decoding:**
   - The user enters the **correct password** to extract the hidden message.
   - If the password is incorrect, access is denied.

## 📌 Example Usage
### **Encoding Process**
```
Enter secret message: Hello World!
Enter a passcode: 1234
```
### **Decoding Process**
```
Enter passcode for Decryption: 1234
Decryption message: Hello World!
```

## 🚀 Future Enhancements
- 🔐 **AES/RSA Encryption:** Adding extra security before embedding messages.
- 🤖 **AI-Powered Steganography:** Using machine learning to optimize encoding.
- 🎥 **Video & Audio Support:** Expanding to hide messages in videos & audio files.
- 📱 **GUI Integration:** Creating a user-friendly application.

## 🤝 Contribution
Contributions are welcome! Feel free to **fork**, **submit pull requests**, or **report issues**.

## 📜 License
This project is licensed under the **MIT License**.

