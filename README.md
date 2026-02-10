# 🚀 AI-POWERED CLOUD STORAGE - **ULTIMATE VERSION**

## ✨ **8 REAL AI FEATURES** - ALL WORKING!



---

## 🎯 AI FEATURES (Fully Functional):

1. ✅ **Smart File Recommendations** - ML algorithm scores files (40% access + 30% recency + 30% importance)
2. ✅ **Anomaly Detection** - Real Isolation Forest detects unusual behavior
3. ✅ **Smart NLP Search** - Intent recognition + semantic matching
4. ✅ **Auto File Tagging** - AI categorizes and tags files automatically  
5. ✅ **Duplicate Detection** - Finds similar files using Jaccard similarity
6. ✅ **Privacy Scanner** - Auto-detects sensitive files
7. ✅ **Usage Prediction** - Forecasts storage needs (30/60/90 days)
8. ✅ **Access Pattern Analysis** - Behavioral tracking for ML training

---

## 💻 TECH STACK:

- **Frontend:** React (clean, modern UI)
- **Backend:** Node.js + Express + MongoDB
- **AI Engine:** Python + FastAPI + scikit-learn
- **ML Algorithm:** Isolation Forest (real machine learning!)
- **Storage:** Local filesystem (no AWS needed for testing!)

---

## ⚡ SUPER QUICK SETUP (15 Minutes):

### **Step 1: Install Dependencies**

```bash
# Backend
cd backend
npm install

# AI Engine  
cd ../ai-engine
pip install -r requirements.txt

# Frontend
cd ../frontend
npm install
```

### **Step 2: Configure Backend**

Create `backend/.env`:

```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/ai_cloud_storage
JWT_SECRET=ai_cloud_secret_key_2024
UPLOAD_DIR=./uploads
AI_ENGINE_URL=http://localhost:5001
```

**Quick create (Windows CMD):**
```cmd
cd backend
echo PORT=5000 > .env
echo MONGODB_URI=mongodb://localhost:27017/ai_cloud_storage >> .env
echo JWT_SECRET=ai_cloud_secret_key_2024 >> .env
echo UPLOAD_DIR=./uploads >> .env
echo AI_ENGINE_URL=http://localhost:5001 >> .env
```

### **Step 3: Start Everything**

**Terminal 1 - AI Engine:**
```bash
cd ai-engine
python main.py
```
✅ Runs on port 5001

**Terminal 2 - Backend:**
```bash
cd backend
npm start
```
✅ Runs on port 5000

**Terminal 3 - Frontend:**
```bash
cd frontend
npm start
```
✅ Opens browser at http://localhost:3000

---

## 🎮 HOW TO TEST AI FEATURES:

### 1. **Smart Recommendations**
- Upload 10+ files
- Access some files 3-5 times each
- Check dashboard "Recommended for You" section
- See AI-scored files!

### 2. **Anomaly Detection**
- Use normally for a while
- Then do 20+ rapid actions
- Check "Security Alerts"
- See ML detect unusual pattern!

### 3. **Smart Search**
- Try: "find my recent tax documents"
- Try: "important files from last month"
- See NLP understand intent!

### 4. **Auto-Tagging**
- Upload file named "invoice_2024.pdf"
- See AI auto-tag: business, year_2024, document
- 90%+ confidence scores!

### 5. **Duplicate Detection**
- Upload same file twice
- Upload similar named files
- Check "Storage Optimization"
- See AI find duplicates!

### 6. **Privacy Scanner**
- Upload file with "passport" in name
- See AI flag as sensitive
- Privacy score drops to 30!

### 7. **Usage Prediction**
- Upload files over time
- Check "Analytics" section
- See 30/60/90 day predictions!

---



## 🏆 WHAT MAKES THIS SPECIAL:

- 🔥 **REAL AI** - Not fake! Actual scikit-learn Isolation Forest
- 🔥 **8 Features** - More than most student projects
- 🔥 **Microservices** - Production architecture
- 🔥 **Working Code** - Everything actually works!
- 🔥 **Modern Stack** - Latest technologies
- 🔥 **Well Documented** - Easy to explain

---

## 🐛 TROUBLESHOOTING:

### MongoDB won't start
```bash
# Install MongoDB Community Edition
# OR use MongoDB Atlas (cloud, free)
# Replace MONGODB_URI in .env with Atlas connection string
```

### AI Engine errors
```bash
cd ai-engine
pip install --upgrade pip
pip install -r requirements.txt
python main.py
```

### Frontend won't connect
```bash
# Make sure backend is running on port 5000
# Make sure AI engine is running on port 5001
# Check browser console for errors
```

---

## ✅ SUCCESS CHECKLIST:

- [ ] MongoDB running
- [ ] AI Engine running (port 5001)
- [ ] Backend running (port 5000)
- [ ] Frontend open (port 3000)
- [ ] Can sign up
- [ ] Can upload files
- [ ] See AI recommendations
- [ ] Search works with NLP
- [ ] Files auto-tagged
- [ ] Anomaly detection active


