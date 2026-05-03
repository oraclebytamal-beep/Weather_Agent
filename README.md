This is the official repository for the "From Code to Cognition" tutorial on building a weather-aware AI agent using Oracle AI Database Private Agent Factory.

🚀 This agent not only fetches real-time weather data but also recommends what to wear, making it a practical example of AI-driven decision support.

📁 **Project Structure**

weather_api_datasource.json          # REST API configuration for weather data
weather_data_extractor_prompt.txt   # Prompt to fetch and structure weather data
outfit_recommender_prompt.txt       # Prompt to generate clothing recommendations

⚙️ **Setup Guide**

1️⃣ Connect the Weather API
- Download weather_api_datasource.json
- Navigate to:
- OCI → Private Agent Factory → Data Sources
- Select:
  1. Source Type: REST API
  2. Upload the JSON file as a new data source

💡 This setup uses a "DummyAuth" configuration, so no API key is required.

2️⃣ **Build the Agent Workflow**

Create a two-step prompt workflow:
🧠 Prompt 1 — Weather Data Extractor
- File: weather_data_extractor_prompt.txt
- Purpose: Fetch and structure weather data
- Recommended Temperature: 0.01
👕 Prompt 2 — Outfit Recommender
- File: outfit_recommender_prompt.txt
- Purpose: Suggest clothing based on weather conditions

3️⃣ **Run the Agent**

Enter any city name in the chat:
- Bangalore
- Mumbai
- Delhi
👉 The agent will:
  1. Retrieve live weather data
  2. Recommend what to wear
   
📺 **Watch the Tutorial**

👉 [Add your YouTube video link here]

🧰 **Tech Stack**

- Oracle Cloud (OCI) — Private Agent Factory
- OCI Generative AI — LLM-powered reasoning and workflow orchestration
- Open-Meteo API — Real-time weather data

💡 **What You’ll Learn**

How to build AI agents using OCI
- Integrating REST APIs without authentication
- Designing multi-step prompt workflows
- Creating real-world AI use cases

⭐ **Support**

If this project helped you:

⭐ Star this repository
🔔 Subscribe to Code to Cognition

📌 **Notes**
This project is designed for learning and demonstration purposes
You can extend it with:
- User preferences (e.g., style choices)
- Location auto-detection
- Multi-day forecasts
