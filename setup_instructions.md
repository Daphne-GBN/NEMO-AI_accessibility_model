# Setup Instructions

Follow the steps below to run the DyslexEdu project locally.

---

## 1. Clone the Repository

Clone the GitHub repository to your local system.

git clone https://github.com/Daphne-GBN/NEMO-AI_accessibility_model.git

cd NEMO-AI_accessibility_model

---

## 2. Install Backend Dependencies

Navigate to the backend folder and install required packages.

cd src/server

npm install

---

## 3. Install Frontend Dependencies

Open another terminal and install frontend packages.

cd src/client

npm install

---

## 4. Run the Backend Server

cd src/server

node index.js

The backend server should start on:

http://localhost:3000

---

## 5. Run the Frontend Application

Open another terminal and run:

cd src/client

npm run dev

The frontend will start on:

http://localhost:5173

---

## 6. Access the Application

Open your browser and go to:

http://localhost:5173

You can now interact with the DyslexEdu interface.

---

## 7. Python AI Module (Optional)

If you want to run the AI module:

cd src/llm

Create a virtual environment:

python -m venv venv

Activate the environment:

Windows:
venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

---

## Requirements

Make sure the following software is installed:

- Node.js (v16 or higher)
- Python (v3.9 or higher)
- npm
- Git

---

## Notes

- Do not upload the `venv` folder to GitHub.
- Ensure `.gitignore` excludes virtual environments and node modules.