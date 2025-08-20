# WhatsApp + ChatGPT Bot (n8n + Twilio + OpenAI)

This repo lets you deploy an **AI-powered WhatsApp bot** on **Railway** or **Render** using:
- [n8n](https://n8n.io) (workflow automation)
- [Twilio WhatsApp API](https://www.twilio.com/whatsapp)
- [OpenAI API](https://platform.openai.com)

---

## 🚀 Quick Deploy (Railway)

1. Fork this repo.
2. Go to [Railway](https://railway.app).
3. Create a new project → Deploy from GitHub.
4. Add these environment variables:

```env
N8N_BASIC_AUTH_ACTIVE=true
N8N_BASIC_AUTH_USER=admin
N8N_BASIC_AUTH_PASSWORD=yourpassword
N8N_PORT=5678
N8N_HOST=0.0.0.0
WEBHOOK_URL=https://<your-app>.up.railway.app
OPENAI_API_KEY=your-openai-key
TWILIO_ACCOUNT_SID=your-twilio-sid
TWILIO_AUTH_TOKEN=your-twilio-auth-token
