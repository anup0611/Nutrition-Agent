# 🥗 AI Nutrition Assistant

An AI-powered virtual assistant that provides healthy diet plans, food suggestions, hydration tips, and wellness advice — all simulated using **IBM Watsonx.ai** and **Granite Foundation Model**. Designed to help users make informed nutrition choices with simple, friendly, multilingual responses.

---

## 🧠 Technologies Used

- IBM Watsonx.ai Studio  
- IBM Granite Foundation Model (`granite-13b-chat` / `granite-3-8b-instruct`)  
- IBM Cloud Object Storage  

---

## ☁️ IBM Cloud Services

- Watsonx.ai Agent Lab  
- IBM Granite Model  
- IBM Cloud Lite Account (Free Tier)  
- IBM Cloud Object Storage  

---

## 🧱 Project Setup

### ✅ Step 1: Access Watsonx.ai
- Visit [IBM Cloud](https://cloud.ibm.com)
- Go to **Watsonx > Watsonx.ai**

### ✅ Step 2: Create Agent Project
- Navigate to **Gen AI > Automating Tasks > Agent Lab**
- Click **Create New Project**
- Project Name: `Nutrition Assistant`
- Attach Cloud Object Storage when prompted

### ✅ Step 3: Build Agent
- Go to **Chat and Build** tab
- Click **Associate Service** → Create or link `watsonx.ai Runtime`
- Choose model: `granite-13b-chat` or `granite-3-8b-instruct`

---

## 💬 Agent Instructions

> “Hi! I’m your Nutrition Assistant. Ask me anything about healthy eating, balanced diets, calories, or hydration!”

### The agent should:
- Recommend diet plans for weight loss, weight gain, or maintenance
- Provide nutritional info on common foods (fruits, vegetables, grains, etc.)
- Suggest balanced meals (veg or non-veg)
- Give hydration and wellness advice
- Explain everything in clear, simple language

⚠️ **Note**: Agent uses simulated knowledge. No real-time API or data fetching.

---

## 🧪 Deployment Instructions

### ✅ Step 1: Save and Deploy
- Click **Save as Agent**
- Click **Deploy** → Generate API Key

### ✅ Step 2: Create Deployment Space
- Click **New Deployment Space**
- Name it: `Nutrition Assistant Deployment`
- Add `watsonx.ai` service

### ✅ Step 3: Deploy Agent
- Select your agent → Confirm → Click **Deploy**

### ✅ Step 4: Test API (Optional)
You can test via Postman or any client:
```json
{
  "messages": [
    {
      "role": "user",
      "content": "Give me a 1500-calorie vegetarian meal plan."
    }
  ]
}



