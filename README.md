# n8n WhatsApp AI Bot - Khaotic Kitchen

This is a prototype conversational commerce automation workflow built using **n8n**, **Meta's WhatsApp Cloud API (Sandbox)**, and **Google Gemini AI**.

## 🚀 Project Overview
This project automates customer interactions for **Khaotic Kitchen**, a tech-forward, delivery-only cloud kitchen virtual restaurant. Because cloud kitchens handle a high volume of repetitive inquiries, this workflow completely automates the customer support system.

### How It Works:
1. **WhatsApp Trigger:** A customer sends a message to the Khaotic Kitchen WhatsApp number.
2. **AI Agent Processing:** The message is sent to an advanced AI Agent powered by the **Google Gemini Chat Model** and equipped with a memory node.
3. **Smart Data Referencing:** The AI Agent automatically interacts with connected Google Sheets tools:
   * 📋 **orders:** To log or append new order details.
   * ❓ **FAQ:** To read and answer common customer queries (store hours, delivery radius, etc.).
   * 📦 **Inventory:** To check active stock and meal availability.
   * 📲 **WhatsApp Send Node:** The final intelligent response is formatted and sent back to the user instantly over WhatsApp.

## 🛠️ Tech Stack Used
* **Automation Platform:** n8n
* **AI Model:** Google Gemini AI (Advanced AI Agent architecture)
* **Messaging Gateway:** Meta WhatsApp Cloud API
* **Database/Storage:** Google Sheets (for Inventory, FAQs, and Orders)

## 📦 Files Included
* `WhatsApp Bot-n8n.json` - The complete export of the n8n workflow. You can easily import this file into your own n8n instance to reproduce the project!
