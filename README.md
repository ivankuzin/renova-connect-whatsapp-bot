# ReNova Connect — WhatsApp Bot

The **WhatsApp Bot** for **ReNova Beauty Hub**, offering the same interaction model as Telegram Bot but through WhatsApp Cloud API.

---

## 🚀 Features

- Send and receive messages via WhatsApp Cloud API  
- Shared interface with Telegram Bot  
- Fetch data from Transform API  
- Template and button support  

---

## 🧩 Technologies

| Component | Technology |
|------------|-------------|
| Framework | pywa |
| API Source | Transform API |
| Deploy | Docker |

---

## ⚙️ Run

```bash
cp .env.example .env
docker-compose up --build
```

---

## 🧰 Environment Variables

| Variable | Description |
|-----------|-------------|
| `WHATSAPP_TOKEN` | WhatsApp API token |
| `WHATSAPP_PHONE_ID` | Business phone ID |
| `API_URL` | Transform API URL |
| `WEBHOOK_URL` | Webhook URL |

---

## 🧾 License
MIT License  
© ReNova Beauty Hub
