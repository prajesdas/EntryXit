EntryXit 🚀
Automated People Counting System for Entry & Exit Monitoring
📌 Overview
EntryXit is an AI-powered people counting system that monitors and tracks individuals entering and exiting a designated area using computer vision techniques. This project leverages OpenCV, NumPy, and Deep Learning to provide real-time insights into crowd movement, making it useful for retail stores, offices, events, and security applications.

🔥 Key Features
✅ Real-Time People Counting – Tracks individuals entering and exiting an area.
✅ Live Video Feed Processing – Uses a webcam or CCTV footage for detection.
✅ AI-Powered Detection – Utilizes object detection models like YOLO or OpenCV's Haar cascades.
✅ Entry/Exit Direction Analysis – Differentiates between incoming and outgoing individuals.
✅ Data Logging & Visualization – Stores and displays entry/exit trends.
✅ Customizable & Scalable – Can be adapted for various environments.

🛠️ Technologies Used
🔹 OpenCV – Image processing and object detection
🔹 NumPy – Array operations and mathematical functions
🔹 Python – Core programming language
🔹 Pandas – Data storage and analytics
🔹 YOLO / Haar cascades – Face and person detection models
🔹 Matplotlib / Seaborn – Data visualization

🎯 Use Cases
🔸 Retail Stores – Monitor customer footfall and optimize store operations.
🔸 Corporate Offices – Track employee movement for security purposes.
🔸 Public Events – Ensure crowd control and safety compliance.
🔸 Smart Buildings – Automate access control and occupancy monitoring.
🔸 Hospitals & Clinics – Track patient and visitor flow.

🚀 Installation & Setup
Step 1: Clone the Repository
sh
Copy
Edit
git clone https://github.com/prajesdas/EntryXit.git
cd EntryXit
Step 2: Install Dependencies
sh
Copy
Edit
pip install -r requirements.txt
Step 3: Run the Application
sh
Copy
Edit
python entryxit.py
🖥️ How It Works
Camera Setup – The system captures a live video feed.
Object Detection – Identifies and tracks people in the frame.
Movement Analysis – Determines whether a person is entering or exiting.
Count Update – Updates the counter and logs data for analysis.
Visualization – Displays real-time counts on-screen and generates reports.
⚡ Demo
🎥 A sample demonstration video is available here (Replace with actual link if available).

🛠️ Customization
Want to modify the project?

Adjust detection models in entryxit.py.
Change logging mechanisms for data storage.
Integrate an alert system for unauthorized access.
📜 License
This project is licensed under the MIT License.

