# Skin Disease Detection using AI

## Project Overview
An AI-powered system that detects common skin diseases from user-uploaded images using a convolutional neural network (CNN) and Flask API.

---

## Features
- Upload skin images and get instant disease predictions  
- Supports top 5 skin diseases classification  
- Simple React frontend for image upload and result display  
- Backend REST API built with Flask serving TensorFlow model  
- PostgreSQL database for user and prediction management

---

## Tech Stack
- Python 3.8+  
- TensorFlow / Keras  
- Flask REST API  
- React.js + Tailwind CSS (frontend)  
- PostgreSQL (database)  
- Deployed on Render / Netlify

---

## Getting Started

### Prerequisites
- Python 3.8+  
- Node.js & npm  
- PostgreSQL (optional for production)

### Setup

#### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
flask run
