## 🏗️ SmartContractor

### 🤖 AI Home Maintenance & Renovation Automation System

---

## ❓ Problem

Home maintenance and renovation services are mostly handled through **manual processes** such as phone calls, WhatsApp messages, and spreadsheets. This leads to multiple operational challenges:

* 😕 Customers struggle to find the right contractor quickly
* 📄 Service requests are poorly documented and hard to track
* 📞 Contractors are contacted manually, causing delays and missed jobs
* ❌ No intelligent matching based on skills, ratings, or experience
* 🔄 Poor communication results in low trust and customer dissatisfaction
* ⏰ No automated reminders, confirmations, or completion tracking
* 📉 Overall system is **slow, error-prone, and not scalable**

---

## ✅ Solution

**SmartContractor** is an **end-to-end AI-powered automation system** that manages the complete lifecycle of a home service request — from submission to invoicing.

---

## ⚙️ How the System Works

* 📝 Accepts customer service requests via a web form
* 🔐 Stores all data securely in a centralized database
* 🧠 Uses AI to analyze uploaded images and issue descriptions
* 🛠️ Automatically matches and ranks contractors based on:

  * Service type
  * Rating
  * Experience
* 📧 Sends automated emails to customers and contractors at every stage
* 📆 Tracks job acceptance, scheduling, completion, and confirmation
* ⏱️ Sends reminders before appointments and after job completion

---

## 🧾 Automated Invoice Workflow

After **customer job-completion confirmation**, the system automatically triggers an **Invoice Generator workflow**:

* 📊 Job details, contractor information, and service data are passed to the invoice workflow
* 🧾 Invoices are generated **without manual intervention**
* 📩 Invoices can be:

  * Stored
  * Emailed
  * Used for accounting and records

---

## 🎙️ AI Voice Chatbot

A **voice-enabled AI chatbot** handles customer and contractor inquiries:

* 📞 Supports job status, scheduling, confirmations, and basic support
* 🔁 Fully integrated with **n8n workflows** and **Supabase**
* ⚡ Provides real-time responses
* 🚀 Eliminates manual billing and support operations
* 📈 Enables a fully scalable service platform

---

## 🧰 Tools & Tech Stack

### 🔄 Automation & Orchestration

* **n8n**

  * Core service workflows
  * Automated invoice generation
  * Voice chatbot orchestration

### 🗄️ Backend & Database

* **Supabase**

  * Tables:

    * `customer_requests`
    * `contractors`
    * `job_completion`
    * `invoices`
  * Storage:

    * Images
    * Invoice files

### 🧠 AI & Intelligence

* **OpenAI (GPT-4o / GPT-4o-mini)**

  * Image analysis
  * Text summarization
  * Conversational intelligence for voice chatbot

* **ElevenLabs**

  * Voice synthesis for AI agent responses
  * Multi-language, natural speech output

### 📬 Communication

* **Gmail API (OAuth2)**

  * Notifications
  * Confirmations
  * Invoice delivery

* **Voice & Telephony**

  * ElevenLabs Voice AI
  * Natural, human-like conversations

### 🎨 Frontend

* **Lovable.dev**

  * Customer forms
  * Contractor forms
  * Scheduling interfaces

* **n8n Schedule Triggers**

  * Reminders
  * Follow-ups
  * Invoice dispatch

---

## 🛠️ How to Set Up

### Step 1: n8n Setup

* Deploy n8n on:

  * Self-hosted server (Docker / VPS), or
  * n8n Cloud
* Enable webhook access with HTTPS

### Step 2: Supabase Setup

* Create a Supabase project
* Configure tables:

  * `customer_requests`
  * `contractors`
  * `job_completion`
* Enable storage bucket for images
* Generate service-role API keys

### Step 3: Credentials Configuration

* Connect Supabase API credentials in n8n
* Configure Gmail OAuth2 credentials
* Add OpenAI API key in n8n

### Step 4: Frontend Integration

Connect **Lovable.dev forms** to n8n webhooks:

* Customer request submission
* Contractor response
* Job completion submission
* Customer confirmation

### Step 5: Workflow Activation

* Test each webhook manually
* Activate the workflows
* Monitor executions and logs in n8n

---

## 🔐 Credentials Information

The following credentials are securely stored inside **n8n**:

* 🔑 Supabase API Key (Service Role)
* 🌐 Supabase Project URL
* 📧 Gmail OAuth2 Client ID & Secret
* ✉️ Gmail authorized email account
* 🧠 OpenAI API Key

**Best Practices**

* ❌ Never expose API keys in frontend code
* 🔄 Rotate keys periodically
* 🌱 Use environment variables where possible

---

## 💰 Cost Estimate (Monthly – Realistic Production Costs)

### 1️⃣ Hosting & Domain (Choose ONE)

**Option A: VPS / SSL / Reverse Proxy**

* Minimum: **$10**
* Maximum: **$20**

**Option B: n8n Cloud (Production)**

* Minimum: **$50**
* Maximum: **$80**

---

### 2️⃣ Backend & Database

* Supabase Pro: **$25** (fixed)

---

### 3️⃣ Frontend & Forms

* Lovable.dev Pro:

  * Minimum: **$50**
  * Maximum: **$75**

---

### 4️⃣ AI & Intelligence

* OpenAI API:

  * Minimum: **$40**
  * Maximum: **$120**

---

### 5️⃣ Voice Chatbot

* ElevenLabs:

  * Minimum: **$22**
  * Maximum: **$99**

---

## 📊 Total Estimated Monthly Cost

### 🔹 Scenario 1: Using VPS Hosting

* **Minimum:** $147 / month
* **Maximum:** $339 / month
  ✅ **Estimated Range:** **$150 – $340 per month**

---

### 🔹 Scenario 2: Using n8n Cloud

* **Minimum:** $187 / month
* **Maximum:** $399 / month
  ✅ **Estimated Range:** **$190 – $400 per month**

---

Demo Video Link: https://drive.google.com/file/d/1easnHxRqNfbpQL9K-XiWzOC4G1871uBS/view?usp=drivesdk

🚀 **SmartContractor** transforms traditional home service operations into a **fully automated, AI-driven, and scalable platform** — reducing costs, improving trust, and enhancing customer experience.

