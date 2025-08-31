# Smart Recipe Generator

Smart Recipe Generator is a **web application** that uses **generative AI** to create custom recipes based on the ingredients you have on hand. Simply snap a picture of your ingredients, and the app will recognize them and generate a unique recipe tailored to your dietary preferences.

---

## How It Works

The application follows a simple, user-friendly workflow:

1. **Upload a Photo**  
   Upload an image of your available ingredients—this could be a picture of items on a countertop or inside a refrigerator.

2. **AI Ingredient Recognition**  
   The image is analyzed by a **generative AI model**, which identifies the ingredients present in the photo.

3. **Select Dietary Preferences** *(Optional)*  
   Users can select from common dietary preferences, such as **Vegetarian** or **Gluten-Free**.

4. **AI Recipe Generation**  
   Using the recognized ingredients and dietary preferences, the app generates a **complete recipe**, including:
   - A creative recipe name
   - A formatted ingredient list
   - Step-by-step cooking instructions

5. **Display and Rate**  
   The final recipe is displayed in a **clean, easy-to-read format**. Users can rate recipes, with ratings saved in the browser’s **local storage**.

---

## Key Features

- **Image-to-Ingredients:** Uses a vision-language model to identify food items from a user-provided image.  
- **Custom Recipe Generation:** Creates unique recipes based on ingredients and dietary needs.  
- **Interactive UI:** Modern, responsive interface built with **Next.js** and **ShadCN UI components**.  
- **Client-Side Rating:** Users can rate recipes, with ratings persisted in local storage.  

---

## Tech Stack

- **Framework:** Next.js (with App Router)  
- **AI:** Firebase Genkit (using Google Gemini models)  
- **Frontend:** React  
- **Styling:** Tailwind CSS  
- **Component Library:** ShadCN UI  
- **Icons:** Lucide React  

---

## Getting Started

To run this project locally, ensure you have **Node.js** and **npm** installed, along with a **Google AI API key**.

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/smart-recipe-generator.git
cd smart-recipe-generator


2. Install Dependencies
npm install

3. Set Up Environment Variables
GEMINI_API_KEY=your_google_ai_api_key_here


4. Run the Development Server
npm run dev


This will start the Next.js frontend on http://localhost:9002
. Open your browser and start using the Smart Recipe Generator!

Contributing

Contributions are welcome!

Fork the repository

Create a new branch for your feature/fix

Submit a pull request

npm run dev
This will start the Next.js frontend on http://localhost:9002.

You can now open your browser and navigate to the address to start using the Smart Recipe Generator.
