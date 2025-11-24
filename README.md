# 🤖 WhatsApp AI Automation Bot (n8n & OpenAI)

## 🌟 Overview
This project demonstrates a robust, scalable, and intelligent WhatsApp automation solution designed to transform customer support and interactive communication for businesses. It seamlessly integrates the **n8n workflow automation platform** with **OpenAI's Large Language Models (LLMs)** to handle complex user queries and media formats automatically.

The goal is to showcase how businesses can achieve **24/7 availability**, significantly **faster response times**, and a **seamless user experience** across various industries (e.g., appointment booking, e-commerce support).

## ✨ Key Features

* **Intelligent Text Handling:** Uses OpenAI to provide contextual and human-like replies to customer inquiries.
* **Multi-Media Support:** Automated processing of **Text, Audio, and Video** messages.
* **Workflow Automation (via n8n):** Handles complex tasks like data logging, CRM updates, and external API calls.
* **Scalable & Customizable:** Built on low-code/no-code principles (n8n) for easy adaptation to different business requirements.
* **Appointment & Booking Management** (Demonstration use-case).

---

## 📺 Demo Video (Working System)

📁 [Access the Bot Demo Videos on Google Drive](https://drive.google.com/drive/folders/1tPaYnoy6zXwrxBnQx5lT4YZjNquB-77Q?usp=sharing)

---

## 🛠️ Technology Stack

| Component | Tool / Library | Role |
| :--- | :--- | :--- |
| **Automation Platform** | `n8n` | Workflow orchestration and webhook handling. |
| **AI Backend** | `OpenAI API (GPT-4/3.5)` | Generative AI for intelligent responses and conversation flow. |
| **Messaging** | `WhatsApp Business API / Twilio` | Primary communication channel. |
| **Programming** | `Python / JavaScript` | (Used for custom functions/scripts within n8n, if any) |
| **Media Handling** | `n8n modules` | Processing and managing audio/video inputs. |

## 🚀 How to Set Up (Local Installation)

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Daniyal-DS/Whatsapp-ai-automation-n8n-openai]
    ```
2.  **n8n Setup:**
    * Deploy n8n locally or on a cloud platform (e.g., Docker).
    * Import the provided workflow JSON file (`whatsapp_bot_workflow.json` - *If you plan to export your n8n workflow*).
3.  **API Keys:**
    * Obtain and configure your **OpenAI API Key** and **WhatsApp API/Twilio Credentials** within the n8n environment variables.
4.  **Webhook Configuration:**
    * Set up a webhook listener in n8n and register its URL with your WhatsApp provider to receive incoming messages.

## 🤝 Contribution & License

This project is maintained by **Daniyal Haider**.

* Feel free to fork the repository and explore the automation logic.
* Licensed under the **MIT License**.
