# CalorieDetector_GeminiApi
This is a simple, single-page web application that uses AI (Groq API with LLaMA 4) to estimate the calorie content of a meal from an uploaded image.

## Setup

1. Clone the repository
2. Copy `config.example.js` to `config.js` and add your Groq API key:
   ```bash
   cp config.example.js config.js
   ```
3. Get a FREE Groq API key from https://console.groq.com
4. Edit `config.js` and replace `your_api_key_here` with your actual key

## Run Locally

```bash
npm install
npm run dev
# or
npx vite
```

Live Demo -->   https://lvk-calorie-ai.netlify.app/

Image Upload: Users can click to upload or drag-and-drop a food photo.

AI-Powered Analysis: Leverages a multimodal AI model to identify food items, estimate their weight, and calculate their approximate calorie count.

Detailed Breakdown: Displays a clear table with each food item, its estimated weight in grams, and its estimated calories.

Clean UI: Built with Tailwind CSS for a modern and responsive design.
