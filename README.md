# 👻 G.H.O.S.T. – AI Personal Assistant

**G.H.O.S.T.** (Guided Human Optimization & Scheduling Tool) is an intelligent AI-powered personal assistant designed to simplify your daily life through automation and smart planning.

Built using **no-code tools** and **generative AI**, Ghost reads your Google Calendar, responds to your Telegram commands, and provides personalized assistance — all in real time.

---

## 🔍 What G.H.O.S.T. Can Do

| Feature | Description |
|--------|-------------|
| 🧠 Smart Chat Assistant | Answers natural queries via Telegram using Gemini AI |
| 📅 Personalized Day Planner | Plans your day based on your calendar events |
| ⏱️ Hour-by-Hour Schedule | Suggests a clean, motivating routine with time blocks |
| 📬 Future-Ready | Email summarization, smart reminders, productivity scoring (coming soon) |

---

## 🧠 How G.H.O.S.T. Works

G.H.O.S.T. is powered by a Make.com automation scenario that integrates:

- 📥 Telegram Bot – the front-end interface where you interact with Ghost
- 📅 Google Calendar – source of your daily events
- ✨ Gemini AI – to generate intelligent responses and plans
- 🔧 Make.com – the no-code automation engine that ties everything together

### 🛠️ Workflow Logic

1. You message your **Telegram bot** with either:
   - “Plan my day” → for schedule generation
   - Any other query → for quick AI answers
2. Ghost checks your Google Calendar (for day planning)
3. Sends context to **Gemini AI**
4. AI responds with a structured plan or answer
5. Telegram bot replies instantly

---

## ⚙️ System Architecture – Make.com Scenario

![Make.com Scenario](demo/screenshots/Screenshot_2025-08-02_222029.png)

This Make.com scenario powers the entire assistant:

- 🟦 **Telegram Bot:** Watches for user messages
- 🟩 **Router:** Decides between a planning flow or general Q&A
- 🔵 **Google Calendar:** Fetches upcoming events
- 🛠️ **Tools Module:** Aggregates events into readable text
- 🌟 **Gemini AI:** Generates a personalized plan or smart response
- 📤 **Telegram Bot:** Sends the final output back to the user

No backend code. Fully modular. Easy to customize.

---

## 🖼️ Screenshots

### ✨ Daily Planner in Action
![Plan my day](demo/screenshots/Screenshot_2025-08-02_222535.png)
> Ghost builds a full daily plan — from breakfast to bedtime — in a structured, motivating format.

---

### 💬 Smart Chat Replies
![Smart replies](demo/screenshots/Screenshot_2025-08-02_222701.png)
> Ask Ghost anything — from productivity tips to travel info — and get helpful replies instantly.

---

### 📅 Your Calendar Behind the Scenes
![Google Calendar](demo/screenshots/Screenshot_2025-07-20_183855.png)
> Ghost pulls structured data from your Google Calendar to ensure your daily plan is relevant and realistic.

---

## 🚀 Getting Started

1. Clone this repo
2. Import `ghost_blueprint_template_redacted.json` into [Make.com](https://make.com)
3. Replace placeholders with:
   - Your **Telegram Bot token**
   - Your **Google Calendar connection**
   - Your **Gemini API credentials**
4. Deploy and start chatting with Ghost via Telegram!

---
## 📁 Project Structure

```bash
Ghost-AI-Personal-Assistant/
├── ghost_blueprint_template_redacted.json
├── README.md
└── demo/
    └── screenshots/
        ├── Screenshot_2025-08-02_222535.png  # plan my day output
        ├── Screenshot_2025-08-02_222701.png  # query response
        ├── Screenshot_2025-07-20_183855.png  # calendar view
        └── Screenshot_2025-08-02_222029.png  # make.com scenario
```
---
## 👨‍💻 Author

**L Anunai Sai Goud**  
Solo-built this AI automation project.  
📫 [LinkedIn](https://www.linkedin.com/in/anunai/)

---

## 📄 License

MIT License
