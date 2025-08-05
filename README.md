# -fund-raise
Intern Donation Dashboard - README
The Intern Donation Dashboard is a web-based application designed to facilitate structured donations by interns or donors to various causes such as Education, Medical, Travel, and Internship support. The platform allows users to choose from a list of registered organizations for each cause and donate a selected amount, thereby supporting efforts that bring positive change to society.
The dashboard features a clean and user-friendly interface with a collapsible sidebar, a top navigation bar, and donation cards for each cause. Each donation card allows users to select an organization and an amount (from ₹500 to ₹2500 in steps of ₹500) before making a donation. The dashboard also highlights a reward system based on total donations, with Bronze, Silver, and Gold badges displayed beside the rewards list.
The project is built using standard web technologies: HTML, CSS, and JavaScript. Firebase is used for backend integration, including authentication and data storage. No Node.js backend is used in this project.
To set up and run this project:

1. Clone or download the project files to your local machine.
2. Open the project folder in your preferred IDE or code editor.
3. Ensure Firebase is configured correctly:
   - Go to the Firebase Console (https://console.firebase.google.com)
   - Create a new project or use an existing one.
   - Enable Firebase Authentication (using Email/Password sign-in method).
   - Create a Firestore Database and configure read/write rules appropriately.
   - Copy the Firebase SDK configuration object and paste it in your JS file.
4. Make sure all assets such as images (badges) are placed in the correct directory.
5. Open ls.html in a browser to begin using the authentication and donation system.
6. Once logged in, users are redirected to the dashboard.html where they can donate and view rewards.
This version does not include profile page integration. The focus is solely on donations, reward display, and organization information. Each donation category has a corresponding page explaining the listed organizations. The site is fully static except for Firebase interactions and can be hosted on platforms like Firebase Hosting.

<img width="1886" height="835" alt="Screenshot 2025-08-05 230828" src="https://github.com/user-attachments/assets/7a5eb62b-5504-41c0-a79d-5c08720037c1" />
<img width="1906" height="864" alt="Screenshot 2025-08-05 230700" src="https://github.com/user-attachments/assets/35e0eb96-912c-4af0-8da8-8a7503bd2b6d" />
<img width="1882" height="835" alt="Screenshot 2025-08-05 230644" src="https://github.com/user-attachments/assets/97fb6adf-ee81-4316-9ac7-83b53242a246" />
<img width="1886" height="804" alt="Screenshot 2025-08-05 230629" src="https://github.com/user-attachments/assets/94293bf6-397a-49c5-be1f-f45a8289f4eb" />
<img width="1885" height="869" alt="Screenshot 2025-08-05 230613" src="https://github.com/user-attachments/assets/6507b5f3-7713-4ce9-b477-3c55abee8984" />
<img width="1892" height="850" alt="Screenshot 2025-08-05 230556" src="https://github.com/user-attachments/assets/98dfc536-3167-4eb5-9a3c-840e01c094a8" />
