# Empowering Informed Food Choices with AI

## 📌 Project Overview

This project, **Empowering Informed Food Choices with AI**, leverages computer vision and natural language processing to help users make healthier food decisions. Users can upload images of food products or nutrition labels, from which the system extracts and analyzes nutritional data using OCR and AI. Users can input any health issues they currently face (e.g., diabetes, allergies), and the AI re-analyzes the already scanned food based on those conditions to provide personalized dietary recommendations. The system is designed with modular architecture and a clean web interface, offering real-time feedback, accessibility, and future scalability.
Additionally, a dedicated news section displays the latest health-related articles-either related to the scanned food or general dietary news-keeping users informed about current trends and food safety.

## 🔐 File Signature Verification (Windows)

This project is signed using GPG to verify its authenticity.

### Steps to Verify:

1. **Download and install GPG** from:  
   https://gpg4win.org

2. **Import the public key**:
   - Open Command Prompt.
   - Navigate to the folder where `my-public-key.asc` is located.
   - Run:
     ```
     gpg --import my-public-key.asc
     ```

3. **Verify the signature**:
   - Ensure both the `.zip` and `.zip.sig` files are in the same folder.
   - Run:
     ```
     gpg --verify Empowering_Informed_Food_Choices_With_AI.zip.sig Empowering_Informed_Food_Choices_With_AI.zip
     ```

   - You should see:
     ```
     Good signature from "Iniya Vasanthan V M <v.m.iniyavasanthan@email.com>"
     ```

---

## ⚙️ After Extracting – Set Up `.env` and `.gitignore`

1. **Create a `.env` file** in the project folder with this content (replace with your real keys):
```
GEMINI_API_KEY=your_gemini_api_key_here 
NEWS_API_KEY=your_newsapi_key_here
```

2. **Create a `.gitignore` file** in the project folder with this content:
```
.env
```

You're now ready to run the project securely without exposing sensitive API keys.
