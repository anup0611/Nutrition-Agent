🥗 AI Agent for Nutrition & Diet Advice
An intelligent nutrition assistant powered by IBM Watsonx.ai and Granite Foundation Model, designed to provide users with healthy diet recommendations, meal plans, calorie info, hydration tips, and general well-being advice — all simulated without external APIs.

🧠 Technologies Used
IBM Watsonx.ai Studio

IBM Granite Foundation Model (granite-13b-chat or granite-3-8b-instruct)

IBM Cloud Object Storage

☁️ IBM Cloud Services
Watsonx.ai Agent Lab

IBM Granite Model

IBM Cloud Lite Account

IBM Cloud Object Storage

🚀 Setup Instructions
✅ 1. Access Watsonx.ai
Log in at IBM Cloud

Navigate to Watsonx > Watsonx.ai

✅ 2. Open Agent Lab
Go to Gen AI > Automating Tasks > Agent Lab

Click Create New Project

Project Name: Nutrition Assistant

Add Cloud Object Storage when prompted

✅ 3. Build the Chat Agent
Inside your project, click Chat and Build

Create or associate watsonx.ai Runtime service

Select model: granite-13b-chat or granite-3-8b-instruct

💬 Agent Instructions (Example)
Hi! I'm your Nutrition Assistant. I can help you with healthy food advice, diet plans, and hydration tips. Just ask!

Your AI should:

Provide balanced diet plans (veg/non-veg)

Suggest meals for weight loss, gain, or maintenance

Recommend hydration and wellness tips

Offer nutritional info on common foods

Use simple, friendly language

Assume users may be beginners or non-experts

Simulate knowledge — no external APIs or live data

💡 Sample Prompts
"What should I eat for a protein-rich vegetarian breakfast?"

"Give me a 1500-calorie meal plan."

"How much water should I drink daily?"

"Is banana good for weight loss?"

"Suggest a balanced diet for a diabetic person."

🧪 Deployment
✅ 1. Save and Deploy
Click Save Agent

Deploy the agent and generate API key

✅ 2. Create Deployment Space
Create a new space: Nutrition Agent Deployment

Associate your Watsonx.ai Runtime

Deploy the agent into this space

✅ 3. Test the API
Use tools like Postman or Curl to test:

json
Copy
Edit
{
  "messages": [
    {
      "role": "user",
      "content": "Suggest a healthy dinner for someone trying to lose weight."
    }
  ]
}
👤 Target Audience
Health-conscious individuals

People with dietary goals (weight loss/gain)

Students or professionals seeking wellness tips

Beginners needing simple diet help

🌟 Key Features
🥗 Meal suggestions for various health goals

💧 Hydration guidance

🍓 Nutrition facts for common foods

🧠 Simple, non-technical answers

💬 Multilingual capability (if extended with model prompts)

🔗 Useful Resources
IBM Cloud Lite Account

Watsonx.ai Studio

Granite Model Info

🔮 Future Scope
🗣️ Voice interface for accessibility

📸 Food photo recognition with multimodal models

📅 Personalized daily nutrition tracking

🧾 Diet journal integration

🌍 Regional diet adaptation (e.g., Indian thali, Mediterranean, etc.)

Built with ❤️ using IBM Watsonx.ai + Granite to support healthier living through AI.


