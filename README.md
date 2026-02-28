# 🍳 Bachelor SamayalAI — Lazy Cooking Assistant

**AI-powered survival cooking assistant for bachelors that turns random ingredients into quick, cheap meals.**

Bachelor SamayalAI helps students and working bachelors decide **what to cook right now** using whatever ingredients they already have. Upload a photo of ingredients or type a list — the system detects items and recommends easy dishes optimized for **time, budget, effort, and available equipment**.

---

## 🚀 Problem

Bachelors often struggle with:

- ❓ What to cook with limited ingredients  
- ⏱️ Lack of time  
- 💸 Tight budgets  
- 🍳 Limited cooking skills  
- 🧰 Few kitchen tools  

This leads to food waste, unhealthy eating, or expensive takeout.

---

## 💡 Solution

Bachelor SamayalAI is an open-source AI assistant that provides:

### 📸 Ingredient → Dish Intelligence

Upload a kitchen photo or enter ingredients → get dish recommendations instantly.

---

## ⭐ Key Features

### 🧠 Ingredient Detection
Detects multiple raw ingredients from messy real-world photos using YOLOv8.

### 🍛 Dish Recommendations
Suggests simple, quick dishes that can be cooked using available ingredients.

---

## 🔥 Bachelor Modes (Unique)

### ⚡ Lazy Mode
Suggests dishes with:

- Fewest steps  
- Minimal effort  
- One-pan cooking  

---

### 💸 Budget Mode
Recommends cheapest meals possible using available ingredients.

---

### ⏱️ Time Mode
Filter by available cooking time:

- 10 minutes  
- 20 minutes  
- 30 minutes  

---

### 🍳 Equipment Mode
Suggest dishes based on tools available:

- Stove  
- Induction  
- Rice cooker  
- Microwave  

---

### 🛒 Missing Ingredient Suggestions
Tells what to buy to unlock more dishes.

Example:

> Buy eggs → Unlock multiple quick meals

---

## 🏥 Health Filter (Optional)

Suggests dishes that are:

- Low oil  
- High protein  
- Diabetic-friendly  

---

## 🧰 Tech Stack

**Detection:** YOLOv8 (Ultralytics)  
**Backend:** FastAPI  
**Frontend:** Streamlit  
**Data:** Open recipe dataset (JSON)  
**Language:** Python  

All components are fully open-source.

---

## 🏗️ How It Works

1. User uploads ingredient photo or text list  
2. YOLO detects ingredients  
3. System builds ingredient list  
4. Rule-based engine matches recipes  
5. Filters applied (time, budget, equipment, health)  
6. Best dishes recommended  

---

## 📦 Installation



Input:

Photo containing:
Onion
Tomato
Eggs

Output:

🍳 Quick Egg Scramble
⚡ 12 minutes
💸 Cheap
🍳 Beginner friendly
🎯 Target Users
- College students
- Hostel residents
- Working bachelors
- Beginners in cooking

##🌍 Impact

Reduces food waste
Promotes home cooking
Saves money
Encourages healthier eating

##📜 License

This project is released under the MIT License.

##🤝 Contributions

Contributions are welcome!
Please open issues or submit pull requests.

##🏆 FOSS Hack 2026 Project

Built for FOSS Hack 2026 — a 31-day open-source hackathon.

##📌 Future Improvements

More recipes

Voice input

Nutrition tracking

Mobile app version

Offline mode

##⭐ If you like this project

Give it a star ⭐ on GitHub!
