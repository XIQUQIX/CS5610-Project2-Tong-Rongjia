# CS5610-Project2-Tong-Rongjia
# Fitness Tracker Web App

## Author
Cai Tong

Email: cai.to@northeastern.edu

Rongjia Sun

Email: sun.rongj@northeastern.edu

## public server
[http://54.211.172.19](http://54.211.172.19:8080/)

## Class Link
[CS5610WebDev Online]

https://northeastern.instructure.com/courses/226004

[project2]

https://northeastern.instructure.com/courses/226004/assignments/2939507

## Project Objective
The Fitness Tracker Web App is a simple web-based application that allows users to register, log in, and track their daily workouts. Users can create, read, update, and delete (CRUD) workout records including sport type, duration, date, and a description. They could also get an exercise plan for their next 4 weeks based on Openai.

The application demonstrates a full-stack implementation using Node.js, Express, MongoDB, and HTML5 with client-side rendering using vanilla JavaScript.

## Features
- User registration and login with authentication
- Add new workout records
- Edit and delete existing workouts
- Display all workouts in a responsive table
- Persistent storage using MongoDB
- Personalized 4-week fitness plan generation using **OpenAI API** based on user goal weight
- Fully deployed web application accessible via HTTPS

## Screenshot
### Sign Up
  <img width="1403" height="676" alt="image" src="https://github.com/user-attachments/assets/b026dec4-79d6-436c-8d53-eb57439439ce" />

### Login
  <img width="1403" height="676" alt="image" src="https://github.com/user-attachments/assets/fec78917-e706-4754-8745-8c305afdb94d" />

### Fitness Record
  <img width="1338" height="676" alt="image" src="https://github.com/user-attachments/assets/f9950960-98f7-45a8-8970-eb1a5239050d" />

### AI Planning
  <img width="1338" height="676" alt="image" src="https://github.com/user-attachments/assets/cbafa00d-3125-48ff-bc6d-6ed87e460381" />

## Technology Requirements

### Core Technologies

- **Backend:** Node.js v16+ with Express.js framework
- **Database:** MongoDB with Atlas (cloud)
- **Frontend:** Vanilla JavaScript (ES6 Modules)
- **Authentication:** Express-session for session-based auth
- **Styling:** Custom CSS3 with responsive design

### Development Tools

- **ESLint:** JavaScript linting and code quality
- **Prettier:** Code formatting and consistency
- **Docker:** MongoDB containerization (recommended)
- **Git:** Version control with clear commit history

### Browser Support

- Modern browsers supporting ES6+ features
- Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- Mobile-responsive design for all screen sizes

## Instructions to Build and Run

### Prerequisites
- Node.js (v18+ recommended)
- npm (comes with Node.js)
- MongoDB (local or cloud instance)
- Optional: Git for cloning the repository

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/fitness-tracker.git
   cd fitness-tracker

2. **install the npm requirement**
   ``` bash
   npm install

### AI Usage
### 1. **ChatGPT**
**Model:** GPT-5
**Responsibility:**  
- Designed backend architecture using Node + Express + MongoDB  
- Helped implement authentication, CRUD endpoints, and data schema design  
- Wrote frontend JavaScript modules for form handling and API requests  
- Drafted and improved documentation (README, design doc, mockups)  
- Assisted in debugging deployment and HTTPS mixed content issues  

### 2. **Claude (Anthropic Claude 3.5 Sonnet)**
**Model:** Sonnet 4.5
**Responsibility:**  
- Refined UI/UX logic for the login and workout pages  
- Suggested improvements to HTML structure and Bootstrap integration  
- Reviewed code organization for maintainability and readability  

### 3. **Grok**
**Model:** Grok4 Fast
**Responsibility:**  
- Contributed to the AI planning logic for generating 4-week personalized fitness plans  
- Assisted with integrating OpenAI API responses into the frontend workflow  
