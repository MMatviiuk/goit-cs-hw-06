## goit-cs-hw-06
Create a web site that interacts with the server over additional sockets and stores information in the MongoDB database.

## Web Application with WebSocket and MongoDB

Project Description
This project is a web application that interacts with a server via WebSocket and stores information in a MongoDB database. The application consists of two main components:
### HTTP Server: 
Handles requests, routes pages and static resources, and interacts with the WebSocket server to send data.
### WebSocket Server: 
Receives data from the HTTP server, saves it to MongoDB, and broadcasts it back to clients.

### Project Structure
http_server.py: Implements the HTTP server using aiohttp for routing requests and serving static files.
socket_server.py: Implements the WebSocket server using websockets for handling messages and motor for MongoDB operations.
Dockerfile.http: Dockerfile for building the HTTP server image.
Dockerfile.websocket: Dockerfile for building the WebSocket server image.
docker-compose.yaml: Configuration for running all services with Docker Compose.
requirements.txt: List of dependencies for the HTTP and WebSocket servers.
storage/data.json: File for storing messages in JSON format.
index.html: Main page of the application.
message.html: Page with a form for sending messages.
style.css: Stylesheet for the web pages.
logo.png: Logo of the application.
error.html: 404 error page.

Start Docker Desktop

Open Windows PowerShell

cd "C:\Users\user\Desktop\_____Go It\4 Computer Systems and Their Fundamentals\Homework6"
docker-compose up

Open a Web Browser: http://localhost:3000

Have fun!

docker-compose down






