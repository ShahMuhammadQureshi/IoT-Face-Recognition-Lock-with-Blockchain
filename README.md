# 🔐 IoT Face Recognition Lock with Blockchain

An innovative Python-based IoT security system that uses facial recognition and blockchain to authenticate users. It securely stores facial data on a MultiChain blockchain and verifies identity in real-time using computer vision and socket communication between client and server.

FR3 => Server (can't be on the Raspberry pie)
multichain should be in the same directory.

The content of [(Multichain)Paste in C] file should be in the C drive with required permission 


---

## 📌 Features

- 👤 **Face Recognition** using `face_recognition` and `OpenCV`
- 🔗 **Blockchain Integration** with `MultiChain` for secure data storage
- 💾 **Image Hashing & Verification** with `SHA-256`
- 📤 **Image Transfer via Sockets** (Client-Server architecture)
- ✅ **Access Control** based on facial similarity
- 📦 **Real-Time Verification** with feedback response

---

## 🧠 Technologies Used

- Python  
- OpenCV  
- face_recognition  
- MultiChain (Blockchain)  
- Socket Programming  
- PIL (Python Imaging Library)  
- Base64 + SHA-256 hashing  
- Client-Server Architecture  

---
```bash
## 📂 File Structure

IoT-Blockchain-FaceLock/
├── server.py # Server code handling socket, blockchain, and face recognition
├── client.py # Client code for capturing and sending images
├── decoded_image.jpg # Output: received verified image from blockchain
├── recieved_image.jpg # Input: raw image from client
├── reg.jpg / ver.jpg # Temp images for register/verify (client-side)
├── multichain.py # BlockChain
└── README.md # Project documentation

yaml
Copy
Edit
```
---

## ▶️ How to Run

### ⚙️ Requirements

Install necessary libraries:

```bash
pip install opencv-python face_recognition pillow multichain
Note: face_recognition may require cmake, dlib, and compatible Python version.
