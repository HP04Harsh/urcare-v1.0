# 🧠 AI Health Assistant  
### Mobile & Desktop Intelligent Health Scoring Platform

An AI-powered Health Assistant that generates personalized health plans based on user onboarding inputs.

Users fill out a structured health assessment form, and the system:

1. Calculates a Health Score 📊  
2. Detects potential health risks (e.g., Diabetes, Lifestyle Issues)  
3. Generates AI-powered personalized health protocols  
4. Provides subscription-based premium access  

Built for both 📱 Mobile and 💻 Desktop platforms.

---

# 🚀 Live Features

## 📝 Smart Onboarding System
Users provide:
- Age
- Weight
- Height
- Lifestyle habits
- Water intake
- Sleep hours
- Medical conditions
- Activity levels

The system processes these inputs and generates a structured health profile.

---

## 📊 AI Health Score Engine

- Dynamic health scoring algorithm
- Risk detection (e.g., diabetes indicators)
- Lifestyle imbalance detection
- Nutrition & hydration analysis
- Personalized improvement insights

---

## 🧠 AI Personalized Health Plan Generator

Based on the user’s score:

- Customized diet suggestions
- Activity & exercise plans
- Sleep optimization protocols
- Diabetes-specific reduction protocols
- Preventive health strategies

AI integration powered by OpenAI API (Serverless via Vercel).

---

## 💳 Subscription System

- PhonePe payment integration
- Monthly & Yearly subscriptions
- Subscription access validation
- Supabase-based subscription management
- Secure backend functions

---

# 🏗️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Vite + React + TypeScript |
| UI | Tailwind CSS + shadcn/ui |
| Backend | Vercel Serverless API |
| Database | Supabase |
| Authentication | Supabase Auth |
| Payments | PhonePe Integration |
| AI Engine | OpenAI API |
| Mobile Support | Capacitor |

---

# 📂 Project Structure

.
├── src/ # React frontend source
├── api/ # Serverless OpenAI functions
├── supabase/ # Database & SQL scripts
├── android/ # Mobile build (Capacitor)
├── public/ # Static assets
├── .github/workflows/ # CI/CD
├── vercel.json # Vercel deployment config
├── package.json
└── README.md


---

# ⚙️ How It Works

1️⃣ User completes onboarding form  
2️⃣ System calculates health score  
3️⃣ AI generates personalized plan  
4️⃣ Subscription unlocks premium protocol  
5️⃣ Data stored securely in Supabase  

---

# 🔐 Security & Best Practices

- Environment variables protected (.env ignored)
- Supabase row-level security
- Secure serverless API calls
- GitHub Actions workflow protection
- Payment verification before subscription activation

---

# 📱 Cross Platform Support

- Fully responsive web app
- Mobile-ready via Capacitor
- Android build included
- Desktop browser optimized

---

# 💡 Example Use Case

If a user:
- Has high BMI
- Low activity
- Poor sleep
- Early signs of diabetes

The AI will generate:

- Blood sugar control diet
- 30-day activity plan
- Sleep improvement strategy
- Hydration correction protocol
- Weekly progress recommendations

---

# 📈 Business Potential

- Preventive Healthcare SaaS
- Subscription-based AI Wellness Platform
- Corporate Wellness Integration
- Digital Health Monitoring Solution

---

# 🛠️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2️⃣ Install Dependencies
npm install
3️⃣ Configure Environment Variables
Create .env file:

VITE_SUPABASE_URL=your_url
VITE_SUPABASE_ANON_KEY=your_key
OPENAI_API_KEY=your_key
PHONEPE_MERCHANT_ID=your_id
4️⃣ Run Development Server
npm run dev
5️⃣ Deploy to Vercel
vercel deploy
🧠 AI Capabilities
Health scoring logic

Personalized health recommendation engine

Risk prediction model

Lifestyle optimization suggestions

⭐ Support

If you like this project, give it a ⭐ and share feedback!
Subscription-gated premium AI responses

