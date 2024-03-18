# Docker Compose Developer Test

**Instructions:**
- **Duration:** 60 minutes
- **Total Marks:** 100
- **Answer all questions.**
- Use the provided `docker-compose.yml` file and your terminal to execute commands.

---

## Section A: Docker Compose Basics (30 marks)

1. What is Docker Compose used for, and how does it differ from Docker?

2. Explain the purpose of the following sections in a `docker-compose.yml` file:
   - `services`
   - `volumes`
   - `networks`

3. Create a `docker-compose.yml` file for a simple web application consisting of two services: a frontend web server (using Nginx) and a backend server (using Node.js). The frontend should serve static files located in `/frontend` directory on the host machine, and the backend should expose port 3000.

## Section B: Container Orchestration (30 marks)

4. Explain the difference between `docker-compose up` and `docker-compose start` commands.

5. How would you scale a service named `web` in a `docker-compose.yml` file to run three containers?

6. Suppose you have a service called `db` in your `docker-compose.yml`. How would you ensure that this service always starts before any other service?

## Section C: Advanced Docker Compose (40 marks)

7. Define environment variables in a `docker-compose.yml` file and explain how they can be used within the services.

8. Integrate a database service (e.g., MySQL) into the previous `docker-compose.yml` you created in question 3. Configure it to use a named volume for persistent storage.

9. Implement a custom network in the `docker-compose.yml` file and connect all services to this network.

10. Create a script that automates the setup process using Docker Compose. This script should:
    - Build all required Docker images.
    - Start all services defined in the `docker-compose.yml` file.
    - Print the logs of all services.

---

**Additional Instructions:**
- For any configurations or commands, assume the latest Docker and Docker Compose versions are being used.
- Write your answers clearly and concisely.
- Ensure your `docker-compose.yml` file is well-formatted and correctly configured.
- Save all configurations and scripts in a single directory for easy review.

**Best of luck!**

---

Save your answers in a markdown file along with any scripts and configurations used during the test.
