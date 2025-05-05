**AI-Powered Learning Management System (LMS)**
This project is an AI-Powered Learning Management System (LMS) that allows institutions to manage courses, upload materials, and let students auto-generate quizzes from course content using Spring AI (Ollama).

**🚀 Features**
**Course Management**: Teachers can create and manage courses.
**Quiz Generation**: AI-powered automatic quiz generation from course content using Spring AI (Ollama).
**Role-based Access**: Two roles: students and teachers, with different functionalities (authentication via Keycloak).
**Student Engagement**: Track student interactions and quiz results.
**Logging & Monitoring**: Centralized logging using the ELK Stack for monitoring system health and student engagement.

**🛠️ Tech Stack**
**Frontend**
**Angular**: Framework for building the user interface.
**Keycloak**: For authentication and role-based access (Student, Teacher).

**Nginx**: For serving the Angular frontend (optional).

**Backend**
**Spring Boot**: For creating microservices.
**Spring AI (Ollama)**: AI for generating quizzes from course content.

**Keycloak**: For user authentication.
**MySQL**: For storing user data and enrollments.
**MongoDB**: For storing course content and quizzes.
**Redis**: For caching frequently accessed data.

**Logging & Monitoring**
ELK Stack: Elasticsearch, Logstash, and Kibana for tracking logs and visualizing student engagement.

