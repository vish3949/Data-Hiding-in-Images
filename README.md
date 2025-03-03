# Secure Data Hiding in Images using Steganography

## 📌 Project Overview
This project provides a **secure and user-friendly** way to **encrypt and decrypt messages within images** using **steganography and password protection**. The message is embedded inside an image using OpenCV and can only be retrieved with the correct password.

## 🛠️ Technologies Used
- **Python** – Programming language
- **OpenCV** – Image processing
- **NumPy** – Array manipulation
- **PyQt6** – Graphical User Interface (GUI)

## 🔥 Features
✔ **Steganography-based encryption** – Hides messages within image pixels.  
✔ **Password-protected decryption** – Ensures secure message retrieval.  
✔ **Graphical User Interface (GUI)** – Easy-to-use interface.  
✔ **No need for external storage** – The message is stored directly in the image.  
✔ **Works with PNG images** – Saves encrypted images in lossless format.

## 📥 Installation
1. **Clone this repository:**  
   ```bash
   git clone https://github.com/vish3949/Data-Hiding-in-Images.git
   cd Data-Hiding-in-Images
   ```
2. **Install dependencies:**  
   ```bash
   pip install opencv-python numpy PyQt6
   ```

## 🚀 Usage
### Encrypt an Image
1. Run the encryption script:
   ```bash
   python encryption.py
   ```
2. Enter the **secret message** and **password**.
3. Click on **Encrypt Image**, and it will generate an encrypted image.

### Decrypt an Image
1. Run the decryption script:
   ```bash
   python decryption.py
   ```
2. Enter the **password** used during encryption.
3. If the password is correct, the **hidden message** will be revealed.


## 🔗 GitHub Repository
👉 (https://github.com/vish3949/Data-Hiding-in-Images)

## 🙌 Contributing
Feel free to fork this repository, raise issues, or contribute enhancements! 😊

