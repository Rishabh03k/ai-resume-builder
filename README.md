# AI Resume Builder

An AI-powered resume builder that provides intelligent suggestions to enhance your resume content. Users can enter their experience, and the system generates ATS-friendly descriptions using AI.

## 🚀 Features
- AI-powered resume suggestions
- Pre-built resume templates
- User-friendly UI with React & Tailwind CSS
- FastAPI backend for AI suggestions
- NLP model trained for resume generation
- Cloud deployment for scalability

## 🛠️ Tech Stack & Tools

### **Frontend:**
- **React.js** - UI framework
- **Tailwind CSS** - Styling framework
- **Vercel** - Deployment for frontend

### **Backend:**
- **FastAPI** - API framework
- **Uvicorn** - ASGI server for FastAPI
- **PyTorch** - Deep learning framework
- **Transformers (Hugging Face)** - Pre-trained NLP models

### **NLP Model:**
- **T5 (Text-to-Text Transformer)** - Fine-tuned for resume suggestions
- **Hugging Face Datasets** - Dataset management
- **Tokenizers** - Text tokenization

### **Cloud Deployment:**
- **Google Cloud Run** - Deploying backend API
- **Firebase** - Authentication & database
- **Google Cloud Storage** - Storing AI models

### **Database:**
- **PostgreSQL (Cloud SQL)** - Storing user resumes
- **MongoDB (optional)** - NoSQL alternative for resumes

## 📂 Project Structure
```
/ai-resume-builder
│── frontend/             # React frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
│── backend/              # FastAPI backend
│   ├── main.py           # API server
│   ├── model.py          # AI model logic
│   ├── requirements.txt
│
│── models/               # Trained AI models
│
│── dataset/              # Training datasets
│
│── README.md             # Project documentation
```

## 🔧 Installation & Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/ai-resume-builder.git
cd ai-resume-builder
```

### **2️⃣ Setup Backend**
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```

### **3️⃣ Setup Frontend**
```bash
cd frontend
npm install
npm run dev
```

### **4️⃣ Train AI Model (Optional)**
```bash
python train_model.py
```

## 🚀 Deployment

### **1️⃣ Deploy Backend to Google Cloud Run**
```bash
gcloud run deploy ai-resume-backend --source .
```

### **2️⃣ Deploy Frontend to Vercel**
```bash
vercel --prod
```

## 💡 Contribution
Feel free to contribute by opening issues or submitting PRs!

## 📄 License
MIT License.

