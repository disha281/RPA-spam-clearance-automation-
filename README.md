# 📬 SpamClearence – Intelligent Gmail Cleaner using UiPath 🤖

## 💡 Overview
Tired of cleaning your Gmail manually?  
**SpamClearence** is an RPA bot built in **UiPath Studio** that automatically scans your Gmail inbox, identifies unwanted or promotional emails, and deletes them based on sender domains or keywords — keeping your mailbox clean and focused.

This project demonstrates how **Robotic Process Automation (RPA)** can eliminate repetitive digital tasks through intelligent, rule-based automation.

---

## 🧩 Workflow Summary

1. **Launch Gmail** using UiPath’s Browser or Google Workspace automation.  
2. **Read and extract sender addresses** from your inbox.  
3. **Compare each sender** against a predefined spam or promotion domain list (e.g., `tirabeauty`, `twitter`, `promo`, etc.).  
4. **Automatically delete or move** matching emails to the **Bin** folder.  
5. **Log every action** for transparency and debugging.

---

## ⚙️ Tech Stack

| Component | Description |
|------------|-------------|
| **UiPath Studio** | Core RPA development environment |
| **Google Workspace / GSuite Activities** | Gmail API integration |
| **System & Mail Activities** | For iterating and manipulating emails |
| **OAuth 2.0 Authentication** | Secure Gmail connection |
| **VB Expressions** | Logic and control flow |

---

## 🚀 How to Use

1. Clone or download this repository.  
2. Open the `.xaml` file in **UiPath Studio**.  
3. Connect your Gmail account under **Google Workspace Scope** or use browser automation.  
4. Add or edit your spam domain list (e.g., in a text or variable array).  
5. Run the bot — watch it scan and clean your inbox automatically!  
6. View logs in **Output Panel** for details of each deleted/moved email.

---

## 🙌 Credits

**Author:** [Disha Rasalkar](https://github.com/disharasalkar)  
🎓 Computer Science Engineer | RPA & AI Enthusiast  

> “Automation is not about doing less — it’s about doing more of what matters.”  

---

