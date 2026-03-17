#Namma Raitha 
It as real time database 
Admin Dashboard
Contract Farming
Farmers marketplace
Community Farming 
AI Crop Diagonsis
Fertilizers, Pestcides, Tools and Seeds Delivary System
Usage Guidelines
Mutlilanguage
Contract Management by Company
Seller Dashboard
Seller Marketplace
Company Dashboard 
Propose Contract farming
Farmer Dashboard



## Instructions to Execute the Project

### Prerequisites
- Node.js (version 18 or higher recommended)
- npm or yarn
- Firebase CLI (for Firebase-related features)

### Installation
1. Clone the repository or ensure you have the project files in your local directory.
2. Install dependencies:
   ```bash
   npm install
   ```

### Environment Setup
1. Create a `.env` file in the root directory if it doesn't exist.
2. Add your Firebase configuration variables to the `.env` file. You can find these in your Firebase project settings:
   ```
   # App
    PORT=3000

    # Weather API
    NEXT_PUBLIC_WEATHERAPI_KEY=your_weather_api_key_here
    WEATHER_API_KEY=your_weather_api_key_here
    
    #GOOGLE_API_KEY=your_google_api_key_here

    # AI
    GEMINI_API_KEY=your_gemini_api_key_here

   ```
   Replace the placeholder values with your actual Firebase project credentials.

### Firebase Setup (Optional)
If you need to deploy or use Firebase services locally:
1. Install Firebase CLI globally:
   ```bash
   npm install -g firebase-tools
   ```
2. Login to Firebase:
   ```bash
   firebase login
   ```
3. Initialize Firebase in your project (if not already done):
   ```bash
   firebase init
   ```

### Running the Project
1. Start the development server:
   ```bash
   npm run dev
   ```
2. Open your browser and navigate to `http://localhost:3000` to view the application.

### Additional Commands
- Build for production: `npm run build`
- Start production server: `npm run start`
- Run linter: `npm run lint`
- Type checking: `npm run typecheck`
