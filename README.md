# SMARTBIN
♻️ SMARTBIN: AI-Powered IoT Waste Management System

📖 Overview

SMARTBIN is an integrated hardware and software solution designed to modernize waste management through the use of Artificial Intelligence and the Internet of Things (IoT). The system automates waste classification using machine learning and provides real-time monitoring of bin capacity to optimize collection logistics.

By combining custom-fabricated hardware with a responsive web dashboard, SMARTBIN delivers a complete end-to-end ecosystem for smarter and more sustainable waste disposal.

✨ Key Features

🧠 Intelligent Waste Classification

Teachable Machine AI integration for image-based waste classification

Real-time identification of waste categories using computer vision

🔌 IoT Hardware Integration

Ultrasonic sensors for real-time bin capacity monitoring

Arduino-based microcontroller system

Custom laser-cut chassis and enclosure design

💻 Web Management Portal

Live dashboard for monitoring bin status

Real-time visualization of capacity and system data

Responsive and user-friendly interface


🛠️ Technology Stack

Category	Technologies

Frontend	HTML5, CSS3, JavaScript

Machine Learning	Google Teachable Machine

Hardware / IoT	Arduino, Ultrasonic Sensors

Fabrication	Laser Cutting

📁 Repository Structure

/teachable_machine/   # Exported AI models for waste classification


index.html            # Main landing page

main.html             # Alternative entry page

dashboard.html        # Real-time monitoring dashboard

scanQR.html           # QR code interaction module

wasteManagement.html  # Waste information / education page

management.js         # Core frontend logic (dynamic updates)

style.css             # Global styling

🚀 Getting Started
# 1. Clone the repository
git clone https://github.com/WYlim1003/SMARTBIN.git

# 2. Navigate into the project folder
cd SMARTBIN

# 3. Open the project
# Simply open index.html in your browser

⚠️ Notes
- This project runs locally in a browser (no server required for UI).
- Live IoT data requires:
  • Arduino hardware setup

   • Ultrasonic sensor integration

  • Proper data communication to the frontend

💡 Future Improvements (Optional but recommended)
Cloud database integration for real-time syncing
Mobile app version (Flutter)
Advanced ML model for higher accuracy
Smart notification system for waste collection
