# 🌐 Simple HTTP Server in Java

This is a **minimal HTTP server** written in pure Java using `ServerSocket`. It's a great project for understanding the fundamentals of networking, HTTP, and how server-client communication works.

When you run this program, it opens port `8080` and responds with the **current date and time** whenever a client (like a browser or Telnet) connects.

---

## 🚀 Features

- ✅ Built with pure Java (no external libraries)
- 📡 Listens on port `8080`
- 📅 Responds with the current server date and time
- 🔁 Handles multiple client connections (looped)
- 🧠 Simple and educational

---

## 📦 How to Run

### 1. Clone the repository

```bash

git clone https://github.com/FaroukAzizi-dev/Simple-java-http-Server.git
cd simple-http-server-java

### 2. Compile the Java file

javac SimpleHTTPServer.java

### 3. Run the server

java SimpleHTTPServer

🌐 How to Test

📁 Option 1: Use a web browser

http://localhost:8080

💻 Option 2: Use Telnet (if installed)

telnet localhost 8080
Then type this and press Enter twice:

GET / HTTP/1.1
Host: localhost



