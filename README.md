# hubspot-onboarding-n8n
Automated post-sale onboarding workflow triggered by HubSpot deal stage changes to coordinate emails, internal tasks, and Slack alerts.
# Customer Onboarding Automation (n8n + HubSpot)

Automated post-sale onboarding workflow triggered by HubSpot deal stage changes.
This system coordinates onboarding emails, internal task creation, and Slack alerts to ensure consistent handoffs from Sales to Customer Success.

---

## 🔧 Tech Stack
- **n8n** – Workflow automation
- **HubSpot CRM** – Deal stages & lifecycle tracking
- **Slack** – Internal onboarding notifications
- **Email Automation** – Customer onboarding sequences

---

## 🚀 What This Automation Does

1. Listens for HubSpot deal stage changes (e.g. Closed Won)
2. Triggers onboarding email sequences automatically
3. Creates internal onboarding tasks for CS or Implementation
4. Sends Slack alerts to the assigned owner and onboarding channel
5. Ensures consistent post-sale handoff and visibility

---

## 🧠 Use Case

Built for teams that need:
- Standardized onboarding across all deals
- Fewer dropped handoffs after close
- Clear ownership between Sales and CS
- Real-time onboarding visibility

---

## 📈 Impact
- Improved onboarding consistency
- Reduced manual handoff work
- Faster time-to-first-touch post-sale
- Clear internal accountability

---

## 🏗 Workflow Overview
See `/docs/architecture.md` for a breakdown of deal stage triggers and automation logic.

---

## 📂 Files
- `/workflows/deal-stage-onboarding-trigger.json` – n8n workflow export
- `/examples/sample-deal-payload.json` – Example HubSpot deal data
- `/docs` – Detailed setup and logic documentation

---

## ⚠️ Notes
- API keys and credentials are excluded
- See `.env.example` for required environment variables

---

## 👤 Author
Built by Jordan  
Solutions Engineering · Customer Onboarding · RevOps Automation
