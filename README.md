# DEVTrails-VABS
AI-Powered Parametric Insurance Platform for India’s Gig Economy
Guidewire DEVTrails 2026 Hackathon Project

An AI-driven parametric micro-insurance platform designed to protect India’s delivery partners from income loss caused by external disruptions like weather, pollution, and social restrictions.

The system uses AI-based risk prediction, automated claim triggering, fraud detection, and instant payouts to ensure financial stability for gig workers.

📌 Table of Contents

Project Overview

Problem Statement

Our Solution

Why This Matters

Target Users

Key Features

Parametric Insurance Model

AI Intelligence Layer

System Architecture

Workflow

Technology Stack

Database Design

API Integrations

Fraud Detection System

Installation Guide

Deployment

Future Enhancements

Impact

Hackathon Team

📖 Project Overview

India’s gig economy delivery partners (Zomato, Swiggy, Amazon, Zepto, etc.) are highly dependent on daily earnings.

However, external disruptions such as:

Extreme weather

Heavy rainfall & floods

High air pollution

Curfews & strikes

Platform outages

can reduce their income by 20–30% monthly.

Currently, there is no insurance system focused on income protection.

Our platform introduces a fully automated AI-powered parametric insurance system that compensates workers instantly when disruptions occur.

❗ Problem Statement

As described in the official Guidewire DEVTrails document :

Gig workers lose income due to uncontrollable external disruptions

No existing insurance covers income loss

Traditional insurance focuses only on:

Health

Vehicle damage

Accidents

Key Challenge:

Build an AI-enabled system that:

Provides income protection

Works on a weekly pricing model

Supports automatic claims & payouts

Includes fraud detection

Constraints:

❌ No health/vehicle/life coverage

✅ Only income loss coverage

✅ Weekly premium model

💡 Our Solution

We propose an AI-powered parametric insurance platform that:

Predicts disruption risks using AI

Dynamically adjusts weekly premiums

Automatically detects events

Instantly triggers payouts

🔥 Key Innovation:

Zero paperwork insurance

Real-time monitoring

Fully automated claims

AI-based fraud prevention

🌍 Why This Solution Matters

Protects gig workers’ daily income

Eliminates manual claim processes

Ensures instant financial support

Reduces fraud using AI

Scales across all cities in India

🎯 Target Users

Delivery partners working in:

Zomato

Swiggy

Amazon

Flipkart

Zepto

Blinkit

Dunzo

⚙️ Key Features
1️⃣ Smart Worker Onboarding

Register with:

Name

Phone

Platform

Location

AI generates a risk profile

2️⃣ Weekly Micro-Insurance Plans
Plan	Weekly Premium	Coverage
Basic	₹5	₹300
Standard	₹8	₹500
Premium	₹12	₹800

✔ Fully aligned with weekly earning cycles

3️⃣ AI-Based Risk Assessment

Weather analysis

Pollution levels

Traffic conditions

Historical disruption data

AI calculates a dynamic risk score

4️⃣ Parametric Claim Automation

No manual claims

Automatic triggers

Instant payout

5️⃣ Fraud Detection System

GPS validation

Duplicate claim detection

Behavioral anomaly detection

6️⃣ Analytics Dashboard

Worker earnings protected

Active policies

Claim history

Admin insights

📊 Parametric Insurance Model

Claims are triggered automatically based on predefined thresholds:

Event	Trigger Condition
Heatwave	Temperature > 48°C
Heavy Rain	Rainfall > threshold
Flood	Water level alert
Pollution	AQI > 400
Curfew	Verified via news
Platform Outage	API failure

✔ Focus: Income Loss Only (as per constraints)

🤖 AI Intelligence Layer
🔹 Risk Prediction Model

Predicts disruptions using:

Weather APIs

Pollution APIs

Historical data

🔹 Dynamic Pricing Model

Adjusts weekly premium

Based on risk score

🔹 Income Loss Estimator

Calculates compensation using:

Working hours

Average earnings

Disruption duration

🔹 Fraud Detection Model

Detects:

Fake claims

GPS spoofing

Unusual activity

🏗️ System Architecture
Frontend (React)
        |
Backend (Node.js / Express)
        |
MongoDB Database
        |
Python AI Services (FastAPI)
        |
AI Monitoring Agents
        |
External APIs
        |
Parametric Engine
        |
Payment Gateway
🔄 Workflow
Step 1: Registration

User signs up → AI generates risk profile

Step 2: Policy Selection

User selects weekly plan

Step 3: Monitoring

AI continuously monitors disruptions

Step 4: Event Detection

System detects disruption automatically

Step 5: Claim Validation

Checks:

Policy status

Location

Event authenticity

Step 6: Instant Payout

User receives compensation instantly

🧰 Technology Stack
Frontend

React.js

Tailwind CSS

Backend

Node.js

Express.js

JWT Authentication

Database

MongoDB

AI Layer

Python

FastAPI

Scikit-Learn

APIs

Weather API

Pollution API

News API

Payments

Razorpay (Test Mode)

UPI Simulation

🗄️ Database Design
Users

userId

name

phone

platform

location

riskScore

Policies

policyId

userId

weeklyPremium

coverage

status

Claims

claimId

eventType

claimAmount

status

🔌 API Integrations

Weather API

Pollution API

Traffic API

Payment Gateway

🛡️ Fraud Detection System

GPS tracking validation

Duplicate claim detection

AI anomaly detection

Historical pattern analysis

⚙️ Installation Guide
git clone https://github.com/your-repo/devtrails-project.git
cd project
Backend
cd backend
npm install
npm run dev
Frontend
cd frontend
npm install
npm start
AI Services
cd ai
pip install -r requirements.txt
uvicorn main:app --reload
🚀 Deployment

Frontend → Vercel / Netlify

Backend → Render / AWS

Database → MongoDB Atlas

AI → Docker + FastAPI

🔮 Future Enhancements

Mobile app

Blockchain-based claims

Real-time delivery platform integration

Advanced AI forecasting

Multi-city expansion

🌟 Impact

Protects millions of gig workers

Ensures financial stability

Reduces fraud

Enables scalable insurance

👨‍💻 Hackathon Team

Guidewire DEVTrails 2026

AI-Powered Insurance Platform for Gig Economy
