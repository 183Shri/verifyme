# ✅ VerifyMe – Age & Identity Verification System 

**VerifyMe** is a web-based age and identity verification tool built for demonstration purposes using **simulated Aadhar cards** and **live webcam selfies**. It performs OCR to extract DOB and uses face recognition to verify identity — all locally in the browser and backend, without relying on any government APIs.

---

##  Tech Stack Summary

| Layer     | Technology/Libraries Used                                      |
|-----------|---------------------------------------------------------------|
| Frontend  | HTML5, CSS3, Bootstrap 5, Vanilla JS (Webcam API)             |
| Backend   | Python 3.11, Flask, Jinja2                                     |
| Face/OCR  | OpenCV, Pillow, `face_recognition`, dlib, pytesseract, Tesseract |
| Utilities | NumPy, base64, datetime                                        |
| Security  | HTTPS (recommended), `.env` for secrets                       |

---

##  Features

- ✅ Upload Aadhar card (image or PDF)
- ✅ Extract DOB using OCR
- ✅ Calculate age and determine if 18+
- ✅ Capture live selfie using webcam
- ✅ Match selfie with Aadhar photo via face embeddings
- ✅ Display match confidence score (e.g., 93.5%)
- ✅ Blur detection for image quality feedback
- ✅ Multilingual OCR support (e.g., Hindi, Tamil)
- ✅ Secure environment config using `.env`
- ✅ HTTPS-ready for secure deployment

---


##  How to Run the Project Locally

###  1. Clone the Repository

\`\`\`bash
git clone https://github.com/tanya-2004/verifyme
cd verifyme
\`\`\`

###  2. Install Dependencies

Make sure you have **Python 3.11** and **Tesseract OCR** installed.

\`\`\`bash
pip install -r requirements.txt
\`\`\`

Install Tesseract:

- **Ubuntu**:
  \`\`\`bash
  sudo apt install tesseract-ocr
  \`\`\`
- **Windows**: [Download here](https://github.com/tesseract-ocr/tesseract/wiki)

###  3. Set Environment Variables

Create a \`.env\` file:

\`\`\`env
FLASK_ENV=development
SECRET_KEY=your_secret_key_here
\`\`\`

### ▶️ 4. Run the Flask Server

\`\`\`bash
python app.py
\`\`\`

Visit: [http://localhost:5000](http://localhost:5000)

---

##  Project Structure

\`\`\`bash
verifyme/
├── static/
│   └── styles.css
├── templates/
│   ├── index.html
│   └── result.html
├── uploads/
│   └── temp image storage
├── app.py
├── requirements.txt
├── README.md
└── verifyme.exe       # ✅ Executable Binary for Windows
\`\`\`

> ✅ \`verifyme.exe\` created using PyInstaller:

\`\`\`bash
pyinstaller --onefile app.py
\`\`\`

---

##  Bonus Features Implemented

- ✅ Match confidence score shown as percentage
- ✅ Multilingual OCR (\`--lang hin\`, etc.)
- ✅ Blur detection using Laplacian variance
- ✅ Webcam capture quality checks
- ✅ \`.env\` for secure secret config
- ✅ Executable \`.exe\` for quick launch (Windows only)

---

##  Security Notes

-  No image data is stored
- ✅ Use **HTTPS** in production (e.g., Flask-Talisman)
- ⚠️ For demo purposes only — do **not** use real Aadhar data

---

##  Demo Video & Presentation

-  [Demo Video (Google Drive / YouTube)](https://drive.google.com/file/d/1AHzhvqY_AcwjYQikRCJI0r7UFFfdg3vo/view?usp=sharing)
-  [Project Presentation (PPT)](https://drive.google.com/file/d/14ynuM6JTk_YZylES_W-C5ZQ37DhAe0jW/view?usp=sharing)

---

##  Submission Checklist

- ✅ GitHub repo with working code
- ✅ README with setup & run instructions
- ✅ Demo video and presentation PPT
- ✅ Bonus features implemented

---

## Built with ❤️ by

**PlayersWhoCode**
