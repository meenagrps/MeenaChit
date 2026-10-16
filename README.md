# Meena Chitfunds — Official WhatsApp Integration
*Operated by Goorac Corporation*

---

## Executive Summary

The Meena Chitfunds WhatsApp Integration platform, developed and maintained by Goorac Corporation, provides an automated communication channel for chit fund subscribers and management. The system streamlines financial operations by dispatching automated monthly due statements, auction summaries, dividend calculations, and instant payment receipts directly via the official Meta WhatsApp Business API.

---

## Core Capabilities

- **Automated Statement Dissemination:** Automatically generates and delivers monthly due reports and subscriber ledger summaries.
- **Auction & Dividend Broadcasts:** Instantly distributes winning bid details and dividend (Kasaru) breakdowns following monthly auctions.
- **Transactional Confirmations:** Delivers digital payment receipts and balance updates upon transaction completion.
- **Secure Webhook Management:** Handles inbound subscriber inquiries and asynchronous delivery status notifications.

---

## Architecture & Technology Stack

- **Runtime Environment:** Node.js, Express.js
- **Data Persistence:** Google Firebase Firestore
- **Messaging Infrastructure:** Meta Cloud WhatsApp Business API
- **Document Generation:** Automated PDF generation for statements and receipts

---

## Configuration & Deployment

### Environment Parameters

```env
PORT=3000
WHATSAPP_API_URL=[https://graph.facebook.com/v17.0/YOUR_PHONE_NUMBER_ID/messages](https://graph.facebook.com/v17.0/YOUR_PHONE_NUMBER_ID/messages)
WHATSAPP_ACCESS_TOKEN=your_secure_access_token
VERIFY_TOKEN=your_webhook_verify_token
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_PRIVATE_KEY="-----BEGIN PRIVATE KEY-----\n..."
FIREBASE_CLIENT_EMAIL=your_firebase_client_email
