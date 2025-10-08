# 🤖 VisiAttend: Automated Attendance System Using Facial Biometrics

## 🌟 Overview
**VisiAttend** is an AI-powered attendance management system that eliminates manual sign-ins through **facial recognition automation**.  
Using a blend of **computer vision (OpenCV)** and **intuitive GUI design (Tkinter)**, the system provides a secure, real-time, and contactless attendance experience.  
Each face becomes a unique digital signature — ensuring **accuracy, transparency, and integrity** in attendance tracking.

> 🎯 Designed for educational institutions, offices, and events — where accuracy and automation matter most.

---

## 🚀 Key Features
| Category | Description |
|-----------|-------------|
| 👤 **Smart Face Recognition** | Detects and identifies faces using **Haar Cascade Classifier** and **LBPH (Local Binary Patterns Histogram)** algorithm. |
| 💡 **Automated Attendance** | Captures, recognizes, and marks attendance automatically with timestamped logs. |
| 🖥️ **User-Friendly GUI** | Developed with **Tkinter**, featuring separate panels for new registrations and existing users. |
| 🔒 **Secure Access** | Password-protected admin access to manage records safely. |
| 🗂️ **Database Management** | Stores user profiles (ID, name, images, and timestamps) in a structured and reliable format. |
| 🧾 **Instant Reporting** | Displays live attendance data including ID, Name, Date, and Time. |
| 🚫 **Proxy Prevention** | Prevents “buddy punching” by validating each person through unique biometric patterns. |

---

## 🧩 System Workflow
### 1️⃣ Registration Phase
- Users enter their **Name** and **ID**.
- The system activates the **webcam** to capture multiple facial samples.
- These images are saved as training data linked to the user’s profile.

### 2️⃣ Training Phase
- The **LBPH recognizer** trains on captured images to map facial features into histograms.
- Each user gets a unique model representation for recognition.

### 3️⃣ Attendance Phase
- Registered users face the webcam to mark attendance.
- ID | NAME | DATE | TIME
  - The results are displayed instantly and stored securely.

---

## 🖼️ GUI Demonstration

### 🪟 Dashboard Interface
![Dashboard]
<img width="1280" height="671" alt="1" src="https://github.com/user-attachments/assets/389ab4a0-e939-43bd-abe1-74faa526973a" />

### 🧾 New Registration Panel
![Registration]
<img width="1280" height="675" alt="2" src="https://github.com/user-attachments/assets/ec54e4a3-c7b6-48fd-b0f4-dd64bb34e857" />
<img width="1280" height="675" alt="3" src="https://github.com/user-attachments/assets/7ba6700e-6f19-4096-b7e4-0b8a63b2e8ee" />

### 📸 Face Capture in Progress
![Capture]<img width="1280" height="673" alt="4" src="https://github.com/user-attachments/assets/6b1a5118-8d09-4529-8b21-aeb184b0337e" />

![Detection]<img width="1280" height="671" alt="5" src="https://github.com/user-attachments/assets/4ea626ad-da8f-4648-84c7-66c82a61848a" />


### 🗃️ Confirmation & Profile Creation
![Capture Confirmed]<img width="1280" height="666" alt="6" src="https://github.com/user-attachments/assets/503168c2-0359-4a56-bd05-550abf72d508" />

![Password Entry]<img width="1280" height="674" alt="7" src="https://github.com/user-attachments/assets/066d75c8-7008-4cfe-b07d-96b706ab2120" />

![Profile Saved]<img width="1280" height="668" alt="8" src="https://github.com/user-attachments/assets/2e239093-1355-41ee-8ebb-c2be9c17138f" />


### 📋 Real-Time Attendance Tracking
![Attendance]<img width="1280" height="675" alt="9" src="https://github.com/user-attachments/assets/11c41025-54f4-4f23-bfdc-63a8fa5fea05" />

![Face Recognition in Action]<img width="1280" height="673" alt="10" src="https://github.com/user-attachments/assets/23aad68c-725c-4cd8-8430-a11da3c1d9cf" />

![Attendance Confirmation]<img width="1280" height="668" alt="11" src="https://github.com/user-attachments/assets/89d3768b-4dfa-4d7b-b03f-1ed980c4d4d1" />


---

## 🛠️ Tech Stack
| Component | Technology |
|------------|-------------|
| **Programming Language** | Python |
| **GUI Framework** | Tkinter |
| **Image Processing Library** | OpenCV |
| **Recognition Algorithm** | LBPH (Local Binary Patterns Histogram) |
| **Database** | CSV / SQLite |
| **IDE** | VS Code / PyCharm |

---

## ⚙️ Installation & Setup

### 🧾 Prerequisites
Make sure you have **Python 3.9+** installed.

### 🔧 Step 1: Clone the Repository
```bash
git clone https://github.com/<your-username>/VisiAttend.git
cd VisiAttend
```
### Step 2: Install Required Libraries
pip install opencv-python
pip install numpy
pip install tk
- The system automatically matches their facial data and records:

### Step 3: Run the Application
python main.py

## 💡 Step 4: Usage

### 🆕 For New Registrations
1. Enter **ID** and **Name**  
2. Click **Take Images** to capture facial samples  
3. Click **Save Profile** to complete registration

### 👥 For Existing Users
- Click **Take Attendance**  
- The system automatically recognizes the face and logs:
ID | NAME | DATE | TIME

---

## 📈 Results
- Achieved **95–98% accuracy** in real-time face recognition under normal lighting conditions.  
- Completely removes manual attendance entry and duplicate records.  
- Successfully tested on multiple users with **consistent performance and precision**.

---

## 🔮 Future Enhancements
- 🤳 **Mobile App Integration:** Enable attendance marking via smartphone cameras.  
- ☁️ **Cloud Synchronization:** Centralize and back up attendance data securely.  
- 🧠 **Deep Learning Models:** Incorporate CNNs to enhance recognition accuracy.  
- 🪪 **Multi-Modal Biometrics:** Combine face, fingerprint, or iris recognition for added security.  
- 📊 **Analytics Dashboard:** Introduce data visualization for attendance insights and trends.

---

## 📚 Academic Significance
**VisiAttend** demonstrates the practical use of **AI-driven computer vision** in modernizing administrative processes.  
It offers a **scalable, contactless, and efficient** attendance solution adaptable for **universities, corporates, and institutions**, minimizing human error and boosting transparency.

---

## 👩‍💻 Author
**Siri Yellu**  
![profile_siri](https://github.com/user-attachments/assets/2a226c10-6c61-4c77-9791-5631d2635a72)
🎓 M.S. in Computer Science — Kennesaw State University    
🔗 [LinkedIn](https://www.linkedin.com/in/siri-reddy-yellu) |
