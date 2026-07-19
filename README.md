# 🌦️ ClimaQuest
### *Will It Rain On My Parade?*

<p align="center">
  <img src="pics/logo.jpg" width="150" alt="ClimaQuest Logo"/>
</p>

<p align="center">
  <strong>An AI-Powered Weather Platform Built for the NASA Space Apps Challenge</strong><br>
  Transforming complex climate data into actionable insights for travelers, engineers, families, and curious minds.
</p>

---

## 📖 Table of Contents
1. [About the Project](#-about-the-project)
2. [Our Vision, Mission & Goals](#-our-vision-mission--goals)
3. [Key Features](#-key-features)
4. [Pages & Screenshots](#-pages--screenshots)
5. [Video Demos](#-video-demos)
6. [Tech Stack](#-tech-stack)
7. [Project Structure](#-project-structure)
8. [Getting Started](#-getting-started)
9. [Our Team](#-our-team)
10. [Use of Artificial Intelligence (AI)](#-use-of-artificial-intelligence-ai)
11. [Data Sources](#-data-sources)
12. [License](#-license)
13. [Links](#-links)

---

## 📖 About the Project

**ClimaQuest** is more than a weather app — it's a comprehensive platform designed to answer the question, *"Will It Rain On My Parade?"* It leverages NASA's historical Earth observation data to help users plan outdoor activities, learn about weather science, teach kids about climate, and support professionals with location-based climate risk data.

Our platform is built on the belief that understanding the weather is for everyone. We combine scientific accuracy with an intuitive, user-friendly interface to make climate knowledge accessible, engaging, and practical.

### The NASA Space Apps Challenge

Our challenge was to construct an app with a personalized interface that enables users to conduct a customized query to determine the likelihood of "very hot," "very cold," "very windy," "very wet," or "very uncomfortable" conditions for any location and date, using Earth observation data. ClimaQuest is our answer to this challenge.

---

## 🌍 Our Vision, Mission & Goals

### 🎯 Our Vision
Our vision is to make climate and weather knowledge accessible to everyone, regardless of age or background. We aim to create a platform that provides accurate and reliable weather data while helping users understand, learn, and plan with confidence. We believe that understanding the weather is not just for scientists—it's for travelers, students, families, and professionals alike.

### 🚀 Our Mission
Our mission is to make climate awareness and planning an easy and engaging experience for everyone by combining scientific accuracy, modern design, and interactive learning tools. We achieve this by:
- Using trusted data sources, including NASA and verified weather APIs.
- Designing an intuitive user interface for effortless navigation.
- Providing educational materials for all age groups.
- Offering personalized travel insights.
- Encouraging environmental awareness.

### 🎯 Our Goal
Our primary goal is to create one unified platform where anyone can easily access everything they need to know about climate and weather—all in one place. This includes viewing 10-day forecasts, learning the science behind predictions, providing educational content for children, helping engineers make informed decisions, and enabling users to plan trips based on accurate weather data.

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| **🌍 Trip Planner** | Plan your travel with confidence by selecting a location and date range. The platform provides personalized weather predictions, safety tips, and activity advice. |
| **🔬 Weather Science** | Dive deep into the science of weather forecasting. Explore mathematical formulas, algorithms, and interactive charts that show historical vs. predicted trends. |
| **👨‍👩‍👧 Teach Your Child** | An interactive learning journey for kids (ages 6-12) featuring animated videos, quizzes, and safety tips about different weather types. |
| **📅 My Weather** | Get a detailed 10-day weather forecast for your current location, with day-by-day breakdowns of temperature, wind, and humidity. |
| **⚙️ Engineering Hub** | A dedicated section for engineers to select the most suitable construction materials based on a city's climate, complete with a material recommendation table and climate risk assessment. |
| **🎨 Dark/Light Theme** | Enjoy a seamless experience with a user-controlled dark or light mode that persists across all pages. |
| **🤖 AI-Powered Insights** | Our AI model analyzes historical climate patterns to predict weather months in advance, turning raw data into practical travel and safety advice. |
| **📊 Interactive Charts** | Real-time data visualization using Chart.js for temperature trends, precipitation, humidity, and wind patterns. |
| **🗺️ Interactive Maps** | Powered by Leaflet.js for an engaging and intuitive location selection experience. |
| **📄 Export Reports** | Download Engineering Hub data as PDF or CSV for offline access and professional use. |

---

## 🖥️ Pages & Screenshots

### 🏠 Home Page
The landing page introduces the project's core question—*"Will It Rain On My Parade?"*—and explains how ClimaQuest uses NASA's historical data to predict the likelihood of adverse weather. It features a "Why Choose ClimaQuest?" section and recommends destinations with favorable weather conditions.

<p align="center">
  <img src="pics/Home%20page.png" width="45%" alt="Home page - dark mode"/>
  <img src="pics/Home%20Page%20light%20mode.png" width="45%" alt="Home page - light mode"/>
  <br/><i>Home page — Dark & Light mode</i>
</p>

<p align="center">
  <img src="pics/Why%20climaQuest.png" width="70%" alt="Why choose ClimaQuest feature grid"/>
  <br/><i>Feature overview grid</i>
</p>

<p align="center">
  <img src="pics/Recommendatiom.png" width="70%" alt="Recommended destinations"/>
  <br/><i>Recommended destinations based on historical weather patterns</i>
</p>

<p align="center">
  <img src="pics/How%20it%20works.png" width="70%" alt="How it works steps"/>
  <br/><i>How It Works — 3-step explanation</i>
</p>

---

### 🧭 Plan Your Trip (Explore Weather)
Users select a destination on an interactive Leaflet map or by typing a place name. After choosing dates and a trip type, the platform displays the probability of extreme conditions and a day-by-day forecast, along with smart, AI-style travel advice.

<p align="center">
  <img src="pics/plan%20your%20journery.png" width="45%" alt="Interactive map"/>
  <img src="pics/choose%20date.png" width="45%" alt="Trip form"/>
  <br/><i>Interactive map and trip planning form</i>
</p>

<p align="center">
  <img src="pics/plan%20your%20journery%20page.png" width="45%" alt="Trip results"/>
  <img src="pics/Advice.png" width="45%" alt="Trip advice"/>
  <br/><i>Weather probability results and smart travel advice</i>
</p>

**Key Features of Plan Your Trip:**
- Choose your destination from a dropdown or directly on the interactive map
- Set exact start and end dates for your journey
- Select trip type: Business, Vacation, Adventure, or Relaxation
- AI-powered forecasts with percentage ratings for hot, cold, rainy, or pleasant conditions
- Personalized packing suggestions and activity recommendations
- Vital safety alerts for severe weather conditions

---

### 🔬 Weather Science & Analytics
This page explains the science behind the forecasting system. It details the prediction methodology with the actual math formulas used, and features a live analytics dashboard with interactive charts (Chart.js) for historical vs. predicted trends.

<p align="center">
  <img src="pics/Weather%20Science.png" width="45%" alt="Prediction methodology"/>
  <img src="pics/Weather%20science%202.png" width="45%" alt="Prediction generation"/>
  <br/><i>Prediction methodology and generation stages</i>
</p>

<p align="center">
  <img src="pics/weather%20science3.png" width="45%" alt="Temperature trends dashboard"/>
  <img src="pics/weather%20science4.png" width="45%" alt="Charts overview"/>
  <br/><i>Temperature trends dashboard and weather analysis charts</i>
</p>

<p align="center">
  <img src="pics/weather%20science5.png" width="45%" alt="ARIMA algorithm"/>
  <img src="pics/weather%20science6.png" width="45%" alt="Neural network"/>
  <br/><i>Prediction algorithms: ARIMA, Neural Networks, and Ensemble Methods</i>
</p>

**What You'll Find:**
- **Prediction Methodology:** Data Collection → Data Processing → AI Modeling with actual math formulas
- **Prediction Generation:** Probabilistic and ensemble forecasting techniques
- **Live Analytics Dashboard:** Historical vs. predicted trends for temperature, precipitation, humidity, wind
- **Quick Stats:** Average temperature, precipitation chance, wind speed, comfort index
- **Algorithm Carousel:** Time Series/ARIMA, Neural Networks, Ensemble Methods with formulas and explanations

---

### 📅 My Weather
A 10-day weather forecast for the user's current location, showing max/min temperature, wind speed, and humidity per day, plus a summary of the odds of various conditions.

<p align="center">
  <img src="pics/my%20weather.png" width="70%" alt="10-day weather forecast"/>
  <br/><i>10-Day Weather Forecast page</i>
</p>

**Features:**
- Automatically detects user's location (defaults to Cairo if permission is denied)
- Each day displayed as an interactive card
- Hover over cards for extended weather predictions
- Summary of odds for Hot/Windy/Humid/Rainy conditions

---

### 👨‍👩‍👧 Teach Your Child (Cosmic Learning Journey)
An interactive, story-driven course that teaches kids (ages 6-12) about weather phenomena through animated 3D videos, simple explanations, safety tips, and quizzes.

<p align="center">
  <img src="pics/Teach%20my%20child.png" width="45%" alt="Chapter video"/>
  <img src="pics/summary%20Tech%20your%20child.png" width="45%" alt="Chapter summary"/>
  <br/><i>Chapter video and summary with safety tips</i>
</p>

<p align="center">
  <img src="pics/Quiz.png" width="45%" alt="Quiz"/>
  <img src="pics/end%20of%20epsoides%20of%20Tech%20your%20child.png" width="45%" alt="Completion screen"/>
  <br/><i>End-of-chapter quiz and completion screen</i>
</p>

**Learning Journey Episodes:**
1. **Rainy Weather** - London, UK
2. **Very Cold Weather** - New York, USA
3. **Windy Weather** - Shanghai, China
4. **Very Hot Weather** - Cairo, Egypt

**Interactive Features:**
- **Animated 3D Videos:** Eye-catching, AI-generated animations with voice-over
- **"Ask for More" Feature:** AI-generated summary and links to NASA resources
- **Take Quiz (Optional):** Fun, engaging quizzes to reinforce learning
- **Learning Journey Map:** Step-by-step exploration path
- **Congratulations Screen:** Celebrating completion of all chapters

---

### ⚙️ Engineering Hub
Built for engineers and planners, this hub provides climate-aware construction insights.

<p align="center">
  <img src="pics/engineering%20hub.png" width="45%" alt="Geotechnical assessment"/>
  <img src="pics/engineering%20hub2.png" width="45%" alt="Hydrological insights"/>
  <br/><i>Geotechnical assessment and hydrological insights</i>
</p>

<p align="center">
  <img src="pics/engineering%20hub3.png" width="45%" alt="Material warnings"/>
  <img src="pics/weatherwise%20Engineering%20hub.png" width="45%" alt="Material recommendations"/>
  <br/><i>Material warnings and material recommendations table</i>
</p>

<p align="center">
  <img src="pics/enginnering%20hub4.png" width="70%" alt="City selection"/>
  <br/><i>City selector for the WeatherWise Engineering Hub</i>
</p>

**Comprehensive Data Provided:**
1. **Geotechnical Assessment:** Seismic hazard level, Predominant soil type
2. **Hydrological Insights:** Soil moisture, Evapotranspiration, Groundwater stress, Drought risk
3. **Renewable Energy Potential:** Solar energy, Wind energy
4. **Material Warnings:** Unsuitable materials with reasons (e.g., wood warping in extreme heat)
5. **Climate Risk Assessment:** Heat days, Aerosol index, Flood events, UV index
6. **Material Recommendations Table:** Scoring on durability, eco-friendliness, cost, lifespan, carbon footprint, availability, resilience, and regulations
7. **Export Options:** Download data as CSV or PDF

**Supported Cities:**
Cairo, Dubai, Tokyo, London, New York, Paris, Sydney, Singapore, Moscow, Toronto, Rio de Janeiro, Cape Town, Mumbai

---

### 📚 Our Resources
A dedicated section crediting and linking to the open data & tools that power ClimaQuest.

<p align="center">
  <img src="pics/resources.png" width="70%" alt="Resources section"/>
  <br/><i>Open-source tools and data sources used in the project</i>
</p>

| Resource | Role in the project |
|----------|---------------------|
| **NASA Earthdata** | Source of satellite/Earth observation data used for historical weather probabilities |
| **Leaflet** | Powers the interactive maps on the Plan Your Trip page |
| **Open-Meteo** | Free open-source weather API |
| **OpenWeather** | Additional open weather API |

---

### ℹ️ About ClimaQuest
This page includes a video tutorial on using the platform, the team's mission statement, a project timeline, and a "Meet Our Team" section.

<p align="center">
  <img src="pics/about%20page.png" width="70%" alt="About page with tutorial"/>
  <br/><i>About page — tutorial video & mission</i>
</p>

<p align="center">
  <img src="pics/journey.png" width="70%" alt="Project journey timeline"/>
  <br/><i>Project timeline: from NASA Space Apps Challenge to public release</i>
</p>

<p align="center">
  <img src="pics/our%20team.png" width="70%" alt="Team members"/>
  <br/><i>The ClimaQuest Team</i>
</p>

**Content Highlights:**
- **Introductory Video:** Step-by-step walkthrough of how to use the platform
- **Mission Statement:** Three pillars - NASA Data Integration, AI-Powered Predictions, Global Accessibility
- **Project Journey Timeline:** From NASA Space Apps Challenge to public release
- **Meet Our Team:** All team members with their roles

---

## 🎬 Video Demos

### Project Introduction Video
An energetic and engaging introduction to the ClimaQuest project, showcasing the platform's vision and excitement.

[![Project Introduction Video](https://img.shields.io/badge/Watch-Project_Intro-red?style=for-the-badge&logo=youtube)](https://drive.google.com/file/d/1QwpGr2r4ObSYYrQ4BtXvHurWlWo2m6Pg/view?usp=drive_link)

*This video provides an overview of the project, building excitement and explaining the core mission of ClimaQuest.*

### Teach Your Child - Episode Sample
A sample of the animated educational content created for children, featuring the "Very Hot Weather" episode set in Cairo.

[![Teach Your Child Episode](https://img.shields.io/badge/Watch-Teach_Your_Child-blue?style=for-the-badge&logo=youtube)](https://drive.google.com/file/d/1HpYnkRvfyEDZBnqUhA5OS-tsIy2q1kwx/view?usp=drive_link)

*This video demonstrates the high-quality, AI-generated animated content designed to make learning about weather fun and accessible for children.*

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla JS) |
| **Theming** | CSS Variables for Dark/Light mode |
| **Charts** | Chart.js |
| **Maps** | Leaflet.js |
| **Animations** | Particles.js |
| **PDF Export** | jsPDF + jsPDF-AutoTable |
| **Icons** | Font Awesome |
| **Fonts** | Google Fonts (Inter) |
| **Data Sources** | NASA Earthdata, Open-Meteo, OpenWeather |
| **Hosting** | Netlify |

---

## 📁 Project Structure

```
Nasa/
├── index.html                 # Home page
├── about.html                 # About Us page
├── exploreweather.html        # Plan Your Trip page
├── weathersience.html         # Weather Science & Analytics page
├── teachyourchild.html        # Kids' learning journey page
├── myweather.html             # 10-day forecast page
├── engineeringhub.html        # Engineering Hub page
├── scripts/
│   ├── homepage.js            # Home page logic + theme switcher
│   └── weathersience.js       # Charts, particles, theme logic
├── styles/
│   ├── homepage.css
│   ├── weathersience.css
│   └── nav.css
└── pics/
    ├── logo.jpg
    ├── van.jpg
    └── final about.mp4
```

---

## 🚀 Getting Started

This is a static front-end project—no build step or package installation required.

### Option 1: Direct Open
1. Download / unzip the project files
2. Open `index.html` directly in your browser

### Option 2: Local Server (Recommended)
```bash
# Using Python
python3 -m http.server 8000

# Using Node.js (live-server)
npx live-server
```

Then open:
```
http://localhost:8000
```

> ⚠️ **Note:** The project loads libraries from CDNs (Chart.js, Leaflet, Font Awesome), so an internet connection is required while running it.

---

## 👥 Our Team

**Developed for the NASA Space Apps Challenge** by a passionate team from **Cairo University, Faculty of Engineering, Egypt**.

> *Our mission goes beyond solving problems—we aim to analyze information, address challenges, and contribute to developing a better Earth. We are not just problem solvers; we carry a vision to find solutions while raising community awareness, especially among youth, and to explain complex issues in simple ways for children—because they are the future.*

| Name | Role |
| :--- | :--- |
| **Mariam Sameh Yasin** | Team Owner |
| **Mariam Mohamed** | Team Member |
| **Habiba Abdelnaser** | Team Member |
| **Shaimaa Abdelaziz Ahmed** | Team Member |
| **Fatma Soror** | Team Member |
| **Mariam Mohamed** | Team Member |

---

## 🤖 Use of Artificial Intelligence (AI)

Our team used Artificial Intelligence (AI) in three main ways for the ClimaQuest project:

### 1. Video Creation
AI was used to generate visual content and animations for the educational videos in the "Teach Your Child" section. This includes 3D animations, character design, and voice-over generation to create engaging, eye-catching content for children.

### 2. Web Development
AI coding assistants were used for:
- Research and ideation
- Generating code snippets
- Debugging and fixing bugs on the front end
- Optimizing performance

### 3. AI Model Training
AI tools helped us:
- Research and write Python scripts
- Train our custom weather prediction model
- Process and analyze historical climate data

> **We have followed all NASA Space Apps Challenge rules by clearly marking AI-generated content and documenting its use.**

---

## 📊 Data Sources

### NASA Data
- **NASA Earth Data** - Primary source of satellite and Earth observation data
- **Giovanni** - For data visualization and analysis
- **Data Rods** - For accessing specific datasets
- **Worldview** - For satellite imagery
- **NASA POWER** - For meteorological and solar data

### Space Agency Partner & Other Data
- **Leaflet** - Interactive mapping library
- **Open-Meteo** - Open-source weather API
- **OpenWeather** - Additional weather data API


---

## 📄 License

This project was built for educational / competition purposes as part of the NASA Space Apps Challenge.

---

## 🔗 Links

| Link | URL |
|------|-----|
| **Live Demo** | [https://climaquest.netlify.app/](https://climaquest.netlify.app/) |
| **Project Demonstration** | [https://drive.google.com/file/d/13utEhXhmwkGFYEdW4ZC4wiLwofcnGLd-/view?usp=sharing](https://drive.google.com/file/d/13utEhXhmwkGFYEdW4ZC4wiLwofcnGLd-/view?usp=sharing) |
| **Project Introduction Video** | [https://drive.google.com/file/d/1QwpGr2r4ObSYYrQ4BtXvHurWlWo2m6Pg/view?usp=drive_link](https://drive.google.com/file/d/1QwpGr2r4ObSYYrQ4BtXvHurWlWo2m6Pg/view?usp=drive_link) |
| **Teach Your Child Sample** | [https://drive.google.com/file/d/1HpYnkRvfyEDZBnqUhA5OS-tsIy2q1kwx/view?usp=drive_link](https://drive.google.com/file/d/1HpYnkRvfyEDZBnqUhA5OS-tsIy2q1kwx/view?usp=drive_link) |
| **GitHub Repository** | [https://github.com/Shaimaa8/climaquest](https://github.com/Shaimaa8/climaquest) |

---

<div align="center">
  <p>
    <strong>🌦️ ClimaQuest — Making Climate Knowledge Accessible to Everyone</strong><br>
    <em>Will It Rain On My Parade?</em>
  </p>
  <p>
    <a href="https://climaquest.netlify.app/">
      <img src="https://img.shields.io/badge/Visit-Live_Demo-00b894?style=for-the-badge&logo=netlify&logoColor=white" alt="Live Demo"/>
    </a>
    <a href="https://github.com/Shaimaa8/climaquest">
      <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repository"/>
    </a>
    <a href="https://drive.google.com/file/d/13utEhXhmwkGFYEdW4ZC4wiLwofcnGLd-/view?usp=sharing">
      <img src="https://img.shields.io/badge/Watch-Project_Demo-red?style=for-the-badge&logo=google-drive&logoColor=white" alt="Project Demo"/>
    </a>
  </p>
</div>