# Workshop 02 – Building a Node.js HTTP Server

This project is a custom Node.js HTTP server. It uses only Node.js core modules (http, fs, path) without any external frameworks like Express.js.

## Features
- Routing: Directs users to the correct HTML pages (/, /about, /contact).
- Static Files: Serves CSS files with the correct MIME type (text/css).
- Security: Blocks path traversal attacks to protect server files.
- Error Handling: Displays custom 404 (Not Found) and 500 (Server Error) pages.
- Bonus API: Provides a JSON endpoint at /api/time that returns the current date and time.

---

## How to run
1. Open your terminal on the project folder
2. Start the server:
   node server.js
3. Ctrl + Click (or Cmd + Click on Mac) the http://localhost:3000 link in your terminal to open it directly, or open your browser and enter the address manually.

---

## Learning reflecion
Building this server helped me understand how web traffic works under the hood.

Key takeaways:

- Core Modules: I learned how to use Node.js built-in tools (http, fs, path) to receive requests, read local files, and send responses.
- HTTP Basics: I now understand the importance of setting correct status codes (200, 404, 500) and headers (like Content-Type) so the browser knows how to read the data.
- Manual Routing: Writing a long if-else chain for routing taught me the basics, but it also showed me why frameworks like Express.js are needed to make larger projects easier to manage.

---
