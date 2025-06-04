# My-Portfolio-Contact-Page-with-Server-Logging
# Node.js & Express.js Contact Form Server

## 🧠 What I Learned
In this project, I explored the fundamentals of **Node.js** and **Express.js** by building a simple backend server to handle a contact form. Specifically, I learned:

- How **Node.js** functions as a backend JavaScript runtime environment.
- How to use **Express.js** to create a basic HTTP server.
- How to serve static files (HTML, CSS) from a `/public` directory.
- How to handle form submissions and process POST requests.
- How to use the **body-parser** middleware to parse incoming form data.
- How to log submitted form data on the server.
- How to redirect users to a thank-you page after form submission.

---

## ⚙️ How the Server Works

- The server is built using **Express.js** and listens on **port 3000**.
- Static files such as HTML and CSS are served from the `/public` folder using:
  
  ```js
  app.use(express.static(path.join(__dirname, "public")));
