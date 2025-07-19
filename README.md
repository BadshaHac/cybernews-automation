# cybernews-automation
# 📰 Cybersecurity News Automation using n8n

This project is an **automated workflow** built with [n8n](https://n8n.io/) that:

- 📥 Fetches the latest Indian cybersecurity news from [NewsAPI](https://newsapi.org/)
- 🧠 Formats a short summary using code
- 📤 Sends the summary to your Gmail inbox daily

---

## 🚀 Features

- 🔐 Focused on **Cybersecurity** & Indian region
- ⏰ Scheduled to run daily (customizable)
- 📬 Uses **Gmail** to send email summary
- 📸 Visual n8n workflow included

---

## 📸 Preview

<img width="1342" height="327" alt="image" src="https://github.com/user-attachments/assets/f563e6c5-cd6e-4084-9bbd-d0df28462222" /> 

##each node preview


<img width="1909" height="930" alt="image" src="https://github.com/user-attachments/assets/23381f64-4734-4bc0-bed4-1fab397ae013" />
<img width="1910" height="902" alt="image" src="https://github.com/user-attachments/assets/5969dc5b-8cdb-4c11-a443-ebe876ef2d6a" />
<img width="1917" height="911" alt="image" src="https://github.com/user-attachments/assets/174440a8-8ac3-4055-aa8e-c56434ac539e" />

Format News Summary code - 

( check out the txt file for code as formatnewsummarycode.txt )

<img width="1919" height="925" alt="image" src="https://github.com/user-attachments/assets/70de1f8b-d038-4a5f-b800-5b95a4202380" />









---

## 🛠️ Tools Used

- [n8n Cloud](https://n8n.io/)
- NewsAPI.org ( https://newsapi.org/v2/everything?q=hacking OR hacker OR cybersecurity  OR penetration testing  OR cybersecurity&sortBy=publishedAt&language=en&pageSize=10&apiKey=API KEY )
- Gmail SMTP (in n8n Email Node)
- JavaScript (for summarizing content)

---

## ⚙️ Setup Instructions

1. Clone this repo or import the `workflow.json` file into your n8n instance
2. Set your **NewsAPI Key** in the HTTP Request node
3. Connect your **Gmail account** in the Email node (use OAuth2 or App Passwords)
4. Deploy on n8n cloud or local instance
5. Set schedule using `Schedule Trigger` node (daily, hourly, etc.)

---

## 📦 Files

| File          | Description                      |
|---------------|----------------------------------|
| `automation email news.json` | Full n8n workflow export         |
| `preview.png`   | Screenshot of n8n visual flow    |
| `README.md`     | This documentation file          |

---

## 🤝 Contribution

Pull requests are welcome! If you want to add new sources, support Telegram/Slack, or improve formatting — feel free to fork and submit.

---

## 📧 Author

Made with 💻 by [BadshaHac]

---

## 🔐 License

MIT License
