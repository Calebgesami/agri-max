# agri-max
a farmers companion
🌱 AgriMax - Smart Farming Assistant

AgriMax is a comprehensive web application designed to empower smallholder farmers with intelligent tools for financial planning, irrigation management, and AI-powered agricultural insights.

https://img.shields.io/badge/AgriMax-Smart%20Farming-brightgreen
https://img.shields.io/badge/React-18.2.0-blue
https://img.shields.io/badge/Node.js-Express-brightgreen
https://img.shields.io/badge/License-MIT-green

🚀 Features

💰 Finance Helper

· Profit/Loss Calculator: Calculate expected profits based on costs and market prices
· Government Scheme Matcher: Find eligible agricultural schemes and subsidies
· Document Checklist: View required documents for scheme applications

💧 Smart Irrigation

· Weather-Integrated Advice: Get irrigation recommendations based on real-time weather
· Smart Alerts: Notifications for rainfall, temperature changes, and soil conditions
· Water Conservation Tips: Optimize water usage for better yield

🤖 AI Assistant

· AI Crop Advisor: Get intelligent crop recommendations based on soil and climate
· Disease Detection: Upload plant images for AI-powered disease identification
· Yield Predictor: AI-powered harvest yield predictions
· Farming Chatbot: 24/7 agricultural expert assistance

📊 Dashboard

· Farm Overview: Quick glance at farm health and status
· Market Prices: Real-time crop price information
· Quick Actions: Easy access to all features

🛠 Tech Stack

Frontend

· React.js with Vite - Fast development and building
· Tailwind CSS - Responsive and modern UI
· Axios - API communication
· Local Storage - Data persistence

Backend

· Node.js with Express.js - Lightweight REST API
· OpenWeatherMap API - Real-time weather data
· CORS - Cross-origin resource sharing

📦 Installation

Prerequisites

· Node.js (v16 or higher)
· npm or yarn
· OpenWeatherMap API key (free tier available)

Setup Instructions

1. Clone the repository

```bash
git clone <repository-url>
cd agrimax
```

1. Backend Setup

```bash
cd backend
npm install
```

1. Configure Environment Variables
   Create a.env file in the backend directory:

```env
OPENWEATHER_API_KEY=your_openweather_api_key_here
PORT=5000
```

1. Frontend Setup

```bash
cd ../frontend
npm install
```

1. Run the Application

Terminal 1 - Backend:

```bash
cd backend
npm run dev
```

Terminal 2 - Frontend:

```bash
cd frontend
npm run dev
```

1. Access the Application

· Frontend: http://localhost:3000
· Backend API: http://localhost:5000

🎯 Usage Guide

For Farmers:

1. Create Profile: Start by creating your farmer profile with farm details
2. Financial Planning: Use the profit calculator and find eligible government schemes
3. Irrigation Management: Get smart watering advice based on weather conditions
4. AI Insights: Consult the AI assistant for crop advice and disease detection

Features in Detail:

💰 Finance Helper

· Input costs (seeds, fertilizer, labor) and expected revenue
· Calculate profit/loss and ROI
· Browse government schemes filtered by eligibility
· View required documents for each scheme

💧 Smart Irrigation

· Automatic weather-based irrigation recommendations
· Alerts for rainfall, helping conserve water
· Soil-type specific advice
· Water conservation tips

🤖 AI Assistant

· Crop Advisor: Get AI-powered crop suggestions
· Disease Detector: Upload plant images for instant analysis
· Yield Predictor: AI-powered harvest predictions
· Chat Assistant: Ask farming-related questions

🔧 API Endpoints

Backend Routes:

· GET /api/schemes - Get government schemes data
· GET /api/weather-advice - Get weather data and irrigation advice
  · Parameters: lat, lon, cropType, soilType, irrigationMethod

External APIs:

· OpenWeatherMap: Weather forecasting
· (Future) Government scheme APIs

🏗 Project Structure

```
agrimax/
├── backend/
│   ├── server.js          # Express server
│   ├── schemes.json       # Government schemes data
│   ├── package.json       # Backend dependencies
│   └── .env              # Environment variables
├── frontend/
│   ├── src/
│   │   ├── components/    # React components
│   │   │   ├── Dashboard.jsx
│   │   │   ├── FarmerProfile.jsx
│   │   │   ├── FinanceDashboard.jsx
│   │   │   ├── IrrigationScheduler.jsx
│   │   │   ├── AIDashboard.jsx
│   │   │   ├── AICropAdvisor.jsx
│   │   │   ├── AIFarmerAssistant.jsx
│   │   │   ├── AIDiseaseDetector.jsx
│   │   │   └── AIYieldPredictor.jsx
│   │   ├── App.jsx       # Main app component
│   │   ├── main.jsx      # React entry point
│   │   └── index.css     # Global styles
│   ├── package.json      # Frontend dependencies
│   └── vite.config.js    # Vite configuration
└── README.md
```

🌟 Key Components

Core Features:

· Farmer Profile Management: Store and manage farmer information
· Financial Tools: Profit calculation and scheme matching
· Weather Integration: Real-time weather-based recommendations
· AI-Powered Insights: Machine learning for agricultural advice

User Experience:

· Responsive Design: Works on desktop and mobile
· Persistent Data: Saves farmer profiles locally
· Intuitive Navigation: Easy-to-use interface
· Visual Feedback: Color-coded alerts and recommendations

🚀 Future Enhancements

Planned Features:

· Mobile App: React Native version
· Multi-language Support: Hindi and regional languages
· IoT Integration: Sensor data from fields
· Blockchain: Supply chain transparency
· Satellite Imagery: Crop health monitoring
· Marketplace: Direct buyer connections
· Weather Alerts: SMS notifications

Technical Improvements:

· Database Integration: MongoDB/PostgreSQL
· Authentication: Farmer login system
· Real APIs: Government scheme integration
· Advanced AI: TensorFlow.js models
· Progressive Web App: Offline functionality

🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. Report Bugs: Create issues for any bugs you find
2. Suggest Features: Propose new features or improvements
3. Code Contributions: Submit pull requests for enhancements
4. Documentation: Help improve documentation and translations

Development Setup:

```bash
# Fork and clone the repository
git clone https://github.com/your-username/agrimax.git
cd agrimax

# Install dependencies
cd backend && npm install
cd ../frontend && npm install

# Start development servers
cd ../backend && npm run dev
cd ../frontend && npm run dev
```

📊 Performance

· Fast Loading: Optimized with Vite
· Responsive: Works on all device sizes
· Offline Capable: Basic functionality without internet
· Lightweight: Minimal bundle size

🐛 Troubleshooting

Common Issues:

1. Weather API Not Working
   · Check OpenWeatherMap API key in .env
   · Verify internet connection
   · Check API rate limits
2. Frontend Not Connecting to Backend
   · Ensure backend is running on port 5000
   · Check CORS configuration
   · Verify proxy settings in vite.config.js
3. Styles Not Loading
   · Restart development server
   · Check Tailwind CSS configuration
   · Verify PostCSS setup

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments

· OpenWeatherMap for weather data API
· Kenyan  Government for agricultural scheme information
· React Community for excellent documentation
· Tailwind CSS for the utility-first CSS framework

📞 Support

For support and questions:

· Create an issue on GitHub
· Email: support@agrimax.com
· Documentation: AgriMax Docs

🌍 Impact

AgriMax aims to:

· 💰 Increase farmer profitability
· 💧 Promote water conservation
· 🤖 Democratize AI for agriculture
· 📱 Bridge the digital divide in farming
· 🌱 Support sustainable farming practices

---

Built with ❤️ for Farmers Worldwide

Making technology accessible to every farmer, one field at a time.