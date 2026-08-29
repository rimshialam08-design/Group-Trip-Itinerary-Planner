# Group-Trip-Itinerary-Planner
A real-time, collaborative travel planning platform featuring AI-generated itineraries, transparent budget splitting, and consensus voting. Built to eliminate group travel friction through user-centric design.

# OOmechala: Intelligent Group Trip Planner

### 📌 Overview
Planning group travel is traditionally plagued by decision fatigue, scattered chat threads, and messy expense ledgers. Applying enterprise design thinking principles, **OOmechala** acts as a centralized, collaborative workspace that minimizes user friction. It brings groups together to seamlessly vote on destinations, auto-arrange day-wise itineraries, and automatically calculate the optimal per-person cost split.

### ✨ Core Features
* **Real-Time Collaboration Rooms:** Dedicated workspaces where users can chat, vote on activities, and visualize their trip on an interactive shared map.
* **Algorithmic Itinerary Routing:** Utilizes graph traversal logic to cluster geographically close locations, minimizing transit time and auto-generating logical daily schedules.
* **AI-Powered Suggestions:** Integrates cloud-based generative AI to parse unstructured group constraints (e.g., "3 days, $500 budget, mostly historical sites") into structured, actionable JSON itineraries.
* **Transparent Expense Settlement:** A built-in relational ledger that tracks shared costs and employs a cash-flow minimization algorithm to calculate the most direct debt settlement routes, eliminating redundant transactions.
* **Frictionless UI/UX:** A responsive, minimalist frontend built with React and Tailwind CSS, focusing on intuitive navigation and visual clarity over complex forms.

### 🛠️ Technical Stack
* **Frontend:** React.js, Tailwind CSS
* **Backend:** Python (FastAPI / Django)
* **Database:** PostgreSQL (with PostGIS for spatial data mapping)
* **Cloud & AI:** Microsoft Azure App Service, Azure OpenAI API

### 🚀 Getting Started

**Prerequisites**
* Node.js (v16 or higher)
* Python 3.9+
* PostgreSQL
