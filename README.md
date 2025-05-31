# 🎯 OpportunityGraph

**Visual Map of Every Internship, Fellowship, Conference, and Grant You Qualify For**

OpportunityGraph is a free, open-source tool that helps students and professionals discover opportunities they’re eligible for — visually. It connects you to internships, fellowships, research programs, scholarships, and grants based on your profile and interests.

## 🚀 Features

- 🔍 Personalized filtering based on your school, GPA, major, and goals  
- 📅 Live deadline tracking and opportunity clustering  
- 🌐 Scraped from trusted sources like Handshake, Simplify, GitHub, NSF, Reddit  
- 🧠 AI-based eligibility prediction and recommendation scoring  
- 🗺️ Visual, interactive map of opportunities (React + D3/Recharts)

## 🛠️ Tech Stack

- **Frontend:** React + Vite + TailwindCSS  
- **Backend:** FastAPI (or Flask), Kafka, PostgreSQL  
- **ML:** PyTorch, torchtune (for opportunity scoring & user clustering)  
- **Infra:** Docker, Kubernetes (for scaling scrapers + API)

## 📂 Project Structure

OpportunityGraph/
├── frontend/ # Vite + React user interface
├── backend/ # FastAPI/Flask backend with Kafka + scrapers
├── data/ # Static mock JSONs until scrapers run live
├── scripts/ # Seeding, testing, or helper scripts


## 📌 Status

> ⚙️ Currently in early MVP stage — setting up frontend & backend structure.

---
