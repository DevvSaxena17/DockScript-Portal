"DOCKSCRIPT PORTAL"

DockScript Portal is a sleek, browser-powered utility dashboard built entirely using HTML, CSS, and JavaScript—with no backend dependencies. It offers a responsive interface that brings together everyday automation tools in one place. Link - https://dockscriptportal.netlify.app/

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

<img width="1891" height="939" alt="image" src="https://github.com/user-attachments/assets/52eed9ff-9e99-43c9-88dd-926b237b1245" />

<img width="1888" height="944" alt="image" src="https://github.com/user-attachments/assets/726fd937-e541-4216-8e49-7dd2ae1d505e" />

<img width="993" height="827" alt="image" src="https://github.com/user-attachments/assets/edfd41fc-b007-43c7-97d1-6bcbaba7bec6" />

<img width="1400" height="898" alt="image" src="https://github.com/user-attachments/assets/28477819-90fd-4617-93be-e024e1c659f9" />

<img width="1881" height="939" alt="image" src="https://github.com/user-attachments/assets/59d2769e-d297-4f94-9dd3-e23519ae406b" />


