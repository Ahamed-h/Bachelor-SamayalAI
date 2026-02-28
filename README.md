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

Bachelor SamayalAI is an open-source AI assistant that:

- Detects ingredients from photos or text input
- Recommends quick, easy, budget-friendly dishes instantly
- Filters recipes by time, budget, equipment, and health needs

---

## ⭐ Key Features

### 🧠 Ingredient Detection
Detects multiple raw ingredients from messy real-world photos using **YOLOv8**.

### 🍛 Dish Recommendations
Suggests simple, quick dishes that can be cooked using available ingredients.

---

## 🔥 Bachelor Modes

| Mode | Description |
|------|-------------|
| ⚡ **Lazy Mode** | Fewest steps, minimal effort, one-pan cooking |
| 💸 **Budget Mode** | Cheapest meals using available ingredients |
| ⏱️ **Time Mode** | Filter by 10 / 20 / 30 minutes cooking time |
| 🍳 **Equipment Mode** | Dishes based on available tools (stove, induction, rice cooker, microwave) |
| 🛒 **Missing Ingredients** | Tells you what to buy to unlock more dishes |

> **Example:** Buy eggs → Unlock multiple quick meals

---

## 🏥 Health Filter *(Optional)*

Suggests dishes that are:

- Low oil
- High protein
- Diabetic-friendly

---

## 🧰 Tech Stack

| Component | Technology |
|-----------|------------|
| Ingredient Detection | YOLOv8 (Ultralytics) |
| Backend | FastAPI |
| Frontend | Streamlit |
| Recipe Data | Open recipe dataset (JSON) |
| Language | Python |

> All components are fully open-source.

---

## 🏗️ How It Works

```
User Input (Photo / Text)
        ↓
YOLOv8 Ingredient Detection
        ↓
Ingredient List Built
        ↓
Rule-Based Recipe Matching
        ↓
Filters Applied (Time / Budget / Equipment / Health)
        ↓
Best Dishes Recommended 🍽️
```

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Ahamed-h/Bachelor-SamayalAI.git
cd Bachelor-SamayalAI

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

---

## 🖥️ Demo

**Input:**

```
📸 Photo containing:
  - Onion
  - Tomato
  - Eggs
```

**Output:**

```
🍳 Quick Egg Scramble
⚡ 12 minutes  |  💸 Cheap  |  🍳 Beginner Friendly
```

---

## 🎯 Target Users

- 🎓 College students
- 🏠 Hostel residents
- 👨‍💻 Working bachelors
- 🔰 Beginners in cooking

---

## 🌍 Impact

- ♻️ Reduces food waste
- 🏡 Promotes home cooking
- 💰 Saves money
- 🥗 Encourages healthier eating

---

## 📌 Future Improvements

- [ ] More recipes
- [ ] Voice input
- [ ] Nutrition tracking
- [ ] Mobile app version
- [ ] Offline mode

---

## 🏆 FOSS Hack 2026 Project

Built for **FOSS Hack 2026** — a 31-day open-source hackathon.

---

## 📜 License

This project is released under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

- 🐛 Open issues for bugs or feature requests
- 🔀 Submit pull requests
- ⭐ Star the repo if you find it useful!

---

*If you found this helpful, give it a star ⭐ on GitHub — it means a lot!*
