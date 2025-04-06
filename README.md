## 🧩 Setup Instructions

### 1️⃣ Clone the Repository


git clone https://github.com/rishika-chaudharyy/AIML-HOTBOT-IMAGE-ANALYZER.git
cd AIML-HOTBOT-IMAGE-ANALYZER


2️⃣ Create and Activate a Virtual Environment (Optional but Recommended)
bash
Copy
Edit
# Create a virtual environment
python -m venv venv

# Activate it
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate


3️⃣ Install Dependencies
pip install fastapi uvicorn python-multipart jinja2


4️⃣ Setup .env for GROQ API 🔐
Create a .env file in the root directory:

GROQ_API_KEY=your_groq_api_key_here


5️⃣ Get Your GROQ API Key
Go to https://console.groq.com/keys

Create a new API Key.

Copy and paste it into your .env file as shown above.


6️⃣ Run the App
uvicorn app:app --reload
App will be live at:
👉 http://127.0.0.1:8000

