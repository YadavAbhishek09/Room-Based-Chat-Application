
Real-time Room-Based Chat Application

--- Overview  ---

This is a real-time chat application where users can create or join rooms and communicate instantly. Built using Spring Boot for the backend and React.js for the frontend, it leverages WebSockets for real-time messaging.

FEATURES

✔ Create and join chat rooms
✔ Real-time messaging using WebSockets
✔ User authentication and authorization
✔ Active user tracking in rooms
✔ Responsive UI with modern design
✔ Optimized backend with Spring Boot

TECH - STACK

FRONTEND :

-React.js
-HTML5, CSS3
-WebSocket client (Socket.io or native WebSockets)


BACKEND :

-Spring Boot
-WebSockets
-Spring Security (for authentication)
-MySQL (Database)
-JPA/Hibernate (ORM)


-- Installation & Setup --

Backend (Spring Boot) Setup

1. Clone the repository:

git clone https://github.com/your-username/chat-app-backend.git
cd chat-app-backend


2. Configure database in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/chat_db
spring.datasource.username=root
spring.datasource.password=yourpassword


3. Build and run the Spring Boot app:

mvn clean install
mvn spring-boot:run



Frontend (React.js) Setup

1. Clone the repository:

git clone https://github.com/your-username/chat-app-frontend.git
cd chat-app-frontend


2. Install dependencies:
    npm install

3. Start the development server:
    npm start



Usage

1. Open the frontend in your browser (http://localhost:3000).
2. Create or join a chat room.
3. Start chatting in real-time!


Future Improvements

🔹 Private messaging
🔹 File sharing support
🔹 User profile customization

Contributing

Feel free to fork this project and submit pull requests!

