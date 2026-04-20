# SMARTBIN
♻️ SMARTBIN: AI-Powered IoT Waste Management System

📖 OVERVIEW
SMARTBIN is an integrated hardware and software solution designed to modernize waste management through the use of Artificial Intelligence and the Internet of Things (IoT). The system automates waste classification using machine learning and provides real-time monitoring of bin capacity to optimize collection logistics. By combining custom-fabricated hardware with a responsive web dashboard, SMARTBIN offers a complete end-to-end ecosystem for smarter, more sustainable waste disposal.

✨ Key Features
🧠 Intelligent Waste Classification
Teachable Machine AI: Integrates lightweight machine learning models to provide computer vision capabilities, automatically identifying and classifying different types of waste as they are deposited.

🔌 IoT Hardware Integration
Real-Time Capacity Monitoring: Utilizes ultrasonic distance sensors connected to an Arduino microcontroller to actively measure how full the bin is.

Custom Fabrication: The physical prototype chassis and sensor enclosures were designed and constructed using precision laser-cutting technology.

💻 Web Management Portal
Live Dashboard: A responsive web interface (dashboard.html) visualizes the real-time status, capacity levels, and operational data of the deployed bins.

🛠️ Technology Stack
Frontend Web Development

HTML5 & CSS3

Vanilla JavaScript (DOM manipulation, dashboard logic)

Machine Learning

Google Teachable Machine (Computer Vision / Image Classification)

Hardware & IoT

Arduino Microcontroller

Ultrasonic Proximity Sensors

Laser Cutter Fabrication

📁 Repository Structure

/teachable_machine/ - Contains the exported AI models used for waste image classification.

index.html / main.html - The primary landing pages and entry points for the web interface.

dashboard.html - The interactive interface for monitoring bin capacity and analytics.

scanQR.html - The module handling quick-response code interactions.

wasteManagement.html - Educational or operational section regarding waste protocols.

management.js - The core client-side logic handling dynamic updates and user interactions.

style.css - Global stylesheets ensuring a responsive and clean user interface.

🚀 Getting Started
To view the web interface locally:

Clone this repository: git clone https://github.com/WYlim1003/SMARTBIN.git

Navigate to the project directory.

Open index.html in your preferred modern web browser.

(Note: Hardware integration requires the physical Arduino setup and sensor array to populate live IoT data).
