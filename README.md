<img width="1849" height="946" alt="indexpage" src="https://github.com/user-attachments/assets/b4ec9674-d9f3-4a3c-a73e-82c26622c9b4" />
<img width="1821" height="992" alt="about" src="https://github.com/user-attachments/assets/9a7efeef-6432-4d97-a645-a307fbf66e80" />
<img width="1826" height="987" alt="contactus" src="https://github.com/user-attachments/assets/167cf5e4-53db-4ef5-adb1-a9837aaf642a" />
<img width="1799" height="975" alt="404" src="https://github.com/user-attachments/assets/cc95a911-8ac2-4781-8d11-1dbae6996d9b" />


📝 InspireHub Static Web Server

📁 Project Structure

inspirehub/
│
├── index.html          # Homepage (Main UI)
├── about.html          # About Us Page
├── contact.html        # Contact Us Page
├── 404.html            # Page Not Found
├── server.js           # Node.js HTTP Server
└── README.md           # Project Documentation (this file)

📌 Objective

Create a basic Node.js web server that serves different static HTML files based on the requested URL path:

    / → index.html

    /about → about.html

    /contact → contact.html

    Any other path → 404.html

⚙️ Technologies Used

    Node.js (for the HTTP server)

    HTML5 (for static content)

    Bootstrap 5 (for styling)

    CSS (for minor custom styles)

🚀 How to Run
1. Setup

Make sure Node.js is installed on your machine.

node -v

2. Run the server

Inside your project folder:

node server.js

3. Visit the site

Open your browser and go to:

http://localhost:8081/


✅ Features

    Dynamic routing using Node.js

    Modular and maintainable code

    Styled using Bootstrap

    Graceful error handling with 404.html and 500 response

📚 Future Enhancements

    Add form submission for Contact page using Express

    Implement routing using Express.js for scalability

    Add image assets and favicon

    Deploy using services like Heroku or Netlify (static hosting)
