# ChatTicket - A Full-Stack Ticketing System
![thumbnail](Img/thumbnail.png)
## 🗂️ Description

ChatTicket is a comprehensive ticketing system that enables users to book tickets for various events and exhibitions. The system consists of a user-friendly frontend built with React and a robust backend powered by FastAPI. It provides features like user authentication, ticket booking, chatbot integration, and analytics.

The project aims to provide a seamless experience for users to discover, book, and manage their tickets, while also offering administrators valuable insights into ticket sales and user activity.

## ✨ Key Features

### **User Features**
* User registration and login functionality
* Browse and book tickets for various events
* View and manage bookings
* Chatbot integration for assistance

### **Admin Features**
* Dashboard for analytics and insights
* Manage users, events, and ticket inventory
* Monitor earnings and ticket sales

### **Technical Features**
* FastAPI backend with MongoDB database
* React frontend with Tailwind CSS styling
* Integration with Dialogflow for chatbot functionality

## 🗂️ Folder Structure

```mermaid
graph TD;
  src-->Frontend;
  src-->Backend;
  Frontend-->components;
  Frontend-->pages;
  Backend-->app;
  Backend-->chatbot;
  app-->models;
  app-->schemas;
  app-->database;
```

## 🛠️ Tech Stack

![FastAPI](https://img.shields.io/badge/FastAPI-009?logo=fastapi&logoColor=white&style=for-the-badge)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=white&style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?logo=mongodb&logoColor=white&style=for-the-badge)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwind-css&logoColor=white&style=for-the-badge)
![Dialogflow](https://img.shields.io/badge/Dialogflow-7645AB?logo=google-cloud-dialogflow&logoColor=white&style=for-the-badge)

## ⚙️ Setup Instructions

* Git clone the repository: `https://github.com/night-spring/ChatTicket.git`
* Install dependencies:
  * Frontend: `npm install` or `yarn install`
  * Backend: `pip install -r requirements.txt`
* Run the application:
  * Frontend: `npm start` or `yarn start`
  * Backend: `uvicorn main:app --host 0.0.0.0 --port 8000`

## 🤖 Chatbot Integration

The chatbot is built using Dialogflow and integrated with the React frontend. It provides users with assistance and support throughout the ticket booking process.

## 📊 Analytics and Insights

The admin dashboard provides valuable insights into ticket sales, user activity, and earnings. It uses data visualization libraries like Recharts to display the data in a clear and concise manner.

## 🚀 Deployment

The application can be deployed on various platforms like Vercel, Heroku, or AWS. The `vercel.json` file provides configuration settings for deployment on Vercel.

## GitHub Actions

The repository uses GitHub Actions for continuous integration and deployment. The workflow file `.github/workflows/main.yml` defines the build and deployment process.



<br><br>
<div align="center">
<img src="https://avatars.githubusercontent.com/u/139033817?v=4" width="120" />
<h3>Debojit Roy</h3>
<p>Focused on backend development and machine learning.</p>
</div>
<br>
<p align="right">
<img src="https://gitfull.vercel.app/appLogo.png" width="20"/>  <a href="https://gitfull.vercel.app">Made by GitFull</a>
</p>
    
