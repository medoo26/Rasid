# RASID – Intelligent Security Monitoring System

## Overview
RASID is an AI-powered security system designed to detect suspicious behavior before incidents occur. It analyzes visual data in real-time using computer vision and machine learning techniques to assess risk levels and generate alerts.

## Problem
Traditional security systems react only after an incident occurs. There is a need for proactive systems that can detect threats early and reduce response time.

## Solution
RASID provides a proactive approach by:
- Monitoring visual data continuously
- Detecting abnormal or suspicious behavior
- Assigning a dynamic risk score
- Triggering alerts when risk exceeds a threshold

## Key Features
- Real-time suspicious behavior detection
- Risk scoring system
- Automated alert mechanism
- Interactive dashboard (frontend)

## System Architecture
- **Frontend:** React (Vite)
- **Backend:** Python (API + processing)
- **AI Layer:** Computer Vision & Machine Learning

## Technologies Used
- Python
- Computer Vision
- Machine Learning
- React (Vite)
- REST APIs

## Project Structure


---

#  Getting Started

##  Requirements
- Python 3.9+
- Node.js (v16 or newer)
- npm

---

##  Run Backend

```bash
cd backend

# Create virtual environment
python -m venv .venv

# Activate (Windows)
.venv\Scripts\activate

# Activate (Mac/Linux)
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run server
python main.py
```
## Run Frontend
```bash

cd frontend

# Install dependencies
npm install

# Run development server
npm run dev
```
