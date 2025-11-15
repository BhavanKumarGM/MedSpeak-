# MedSpeak - AI-Powered Healthcare Platform

MedSpeak is a comprehensive healthcare management system that leverages AI to streamline medical consultations, patient management, and clinical documentation.

## 🚀 Features

### 🔐 Role-Based Access Control
- **Premium Login System** with modern UI/UX
- **Nurse Dashboard** - Patient care and consultation management
- **Doctor Dashboard** - Patient diagnosis and treatment recommendations

### 🏥 Patient Management
- Patient registration and UHID generation
- Consultation history tracking
- Emergency patient prioritization
- WhatsApp-like patient queue interface

### 🤖 AI-Powered Features
- **Speech-to-Text** transcription using Web Speech API
- **Gemini AI Integration** for medical summaries
- **Bullet Point Summaries** from consultation transcripts
- **Medicine Recommendations** based on symptoms
- **Emergency Detection** with automatic alerts

### 📊 Dashboard Features
- Real-time patient queue management
- Emergency case prioritization with dialog alerts
- Consultation history with PDF export
- Prescription management
- AI-generated medical insights

## 🛠️ Technology Stack

### Frontend
- **Next.js 16** with TypeScript
- **Tailwind CSS** for styling
- **Radix UI** components
- **React Hook Form** for form management
- **jsPDF** for PDF generation

### Backend
- **Node.js** with Express
- **MongoDB** with Mongoose
- **Google Gemini AI** for medical summaries
- **OpenAI API** support
- **Ollama** integration for offline AI

### AI & ML
- **Google Gemini 1.5 Flash** for text generation
- **Web Speech API** for voice recognition
- **LlamaIndex** for document processing

## 📦 Installation

### Prerequisites
- Node.js 18+
- MongoDB Atlas account
- Google Gemini API key

### Backend Setup
```bash
cd "Swasya AI backend"
npm install
```

Create `.env` file:
```env
PORT=5000
GEMINI_API_KEY=your_gemini_api_key
MONGO_URI=your_mongodb_connection_string
OLLAMA_HOST=http://localhost:11434
```

### Frontend Setup
```bash
cd "Swasya AI frontend"
npm install
```

### Running the Application
```bash
# Start both servers
start-all.bat

# Or start individually
start-backend.bat
start-frontend.bat
```

## 🌐 Access URLs
- **Frontend**: http://localhost:3000
- **Backend**: http://localhost:5000
- **Login Page**: http://localhost:3000/login

## 👥 User Roles

### Nurse Dashboard
- Patient registration and management
- Consultation recording and transcription
- AI-powered summary generation
- Prescription upload and management

### Doctor Dashboard
- Patient queue with emergency prioritization
- WhatsApp-like patient interface
- AI-generated medicine recommendations
- Emergency case alerts and notifications

## 🔧 Key Features

### Emergency Management
- Automatic detection of emergency keywords
- Priority sorting of patient queue
- Emergency dialog alerts for doctors
- Red-themed emergency indicators

### AI Integration
- **Gemini AI** for medical text generation
- **Bullet point summaries** from transcripts
- **Medicine recommendations** based on symptoms
- **Structured medical documentation**

### Modern UI/UX
- **Glass morphism** design elements
- **Dark gradient** backgrounds
- **Animated components** and transitions
- **Responsive design** for all devices

## 📱 Mobile Support
- Responsive design for tablets and phones
- Touch-friendly interface elements
- Mobile-optimized navigation

## 🔒 Security Features
- Environment variable protection
- CORS configuration
- Input validation and sanitization
- Secure API endpoints

## 📈 Performance
- **Next.js 16** with Turbopack for fast builds
- **MongoDB** for scalable data storage
- **Optimized API calls** with caching
- **Lazy loading** for better performance

## 🤝 Contributing
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License
This project is licensed under the MIT License.

## 🆘 Support
For support and questions, please open an issue on GitHub.

---

**MedSpeak** - Transforming healthcare with AI-powered solutions 🏥✨