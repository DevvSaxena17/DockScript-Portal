"UTILIHUB JS"

UtiliHub JS is a sleek, browser-powered utility dashboard built entirely using HTML, CSS, and JavaScript—with no backend dependencies. It offers a responsive interface that brings together everyday automation tools in one place. Link - https://dockscriptportal.netlify.app/

🔧 Features:-

📸 Camera - Capture high-quality photos from your webcam, preview them, download instantly, or send via email.

🎥 Video Recorder - Record video using your webcam, preview and download it, or embed the video directly into an email.

📧 Email Sender - Send personalized emails with subject, body, and attachments—powered by EmailJS.

📲 WhatsApp Messenger - Quickly open WhatsApp Web with pre-filled message text for any phone number (with country code).

🐳 Docker Commands Panel
Execute commonly-used Docker commands with inline explanations to help users understand their use. Includes command templates, syntax reference, and outputs shown in a styled terminal block.

🛠️ Built With:-

HTML5

CSS3 (with responsive design, custom variables, and animations)

JavaScript (Vanilla)

EmailJS for serverless email integration

🚀 How It Works:-

Camera & Video Access - Utilizes the navigator.mediaDevices.getUserMedia() API for webcam and microphone access.

Photo Capture - Snapshots are rendered via <canvas> and converted to base64 for preview/download/email.

Video Recording - Uses MediaRecorder API to encode .webm video blobs which are downloadable and embeddable in email.

Email Sending - Integrates EmailJS with pre-defined templates to send data-rich messages without any server setup.

WhatsApp Chat - Launches a wa.me link using user input for number and message, opening directly in WhatsApp Web.

✉️ EmailJS Setup
To enable email functionality:

1. Sign up at EmailJS

2. Create a service and a template

3. Replace these placeholders in your script:

emailjs.init("YOUR_PUBLIC_KEY");

emailjs.send("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", params);

Developed by:-

Devv Saxena

Screenshots :-

<img width="1886" height="941" alt="image" src="https://github.com/user-attachments/assets/ab495cb9-ef3b-47d7-9053-b18ca3f37419" />


<img width="1372" height="922" alt="image" src="https://github.com/user-attachments/assets/cd182b33-9f2f-46f5-9847-04b681fece15" />


<img width="1340" height="691" alt="image" src="https://github.com/user-attachments/assets/67c23989-4efc-4abc-8d27-f9e81d968ec6" />


<img width="1141" height="861" alt="image" src="https://github.com/user-attachments/assets/0d6a7d43-c244-40be-b659-fe7e89add8d4" />


<img width="1885" height="941" alt="image" src="https://github.com/user-attachments/assets/25e84c15-8883-4b68-82a5-802aafa918b8" />




