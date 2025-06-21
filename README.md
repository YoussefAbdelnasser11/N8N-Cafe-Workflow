# N8N-Cafe-Workflow
# ☕ Café Automation Workflows using n8n

This project includes two automation workflows built with [n8n](https://n8n.io) to streamline café operations through scheduled tasks and automated order processing.

---

## 🔧 Workflows Included

n8n-cafe-automation/
│
├── README.md
├── Schedule_tasks.json
└── Orders_Flow.json

### 1. 📆 `Schedule_tasks.json`
**Purpose:**  
Sends daily task emails to café staff every morning at 8:00 AM.

**Key Features:**
- Scheduled Trigger at 8:00 AM daily
- Reads tasks from a Google Sheet
- Formats them using a code node
- Sends the task list via Gmail to the staff

---

### 2. 🧾 `Orders_Flow.json`
**Purpose:**  
Handles customer orders submitted via a form and automates notification and storage.

**Key Features:**
- Accepts orders through a public form
- Stores the customer name, order, and price in Google Sheets
- Sends order details by email to the barista for preparation

---

## 📂 Files

| File Name             | Description                          |
|-----------------------|--------------------------------------|
| `Schedule_tasks.json` | Daily scheduled task notification    |
| `Orders_Flow.json`    | Customer order form and automation   |

---

## 🛠️ Technologies Used

- [n8n](https://n8n.io)
- Google Sheets
- Gmail (OAuth2)
- Python (Code node)

---

## 🚀 How to Use

1. Import `.json` files into your n8n instance.
2. Set up Google Sheets and Gmail credentials.
3. Adjust email addresses and sheet URLs as needed.
4. Activate the workflows!

---

## 🧠 Author

Built by [Youssef Abdelnasser](https://www.linkedin.com/in/youssef-abdalnasser-33705b262/)
