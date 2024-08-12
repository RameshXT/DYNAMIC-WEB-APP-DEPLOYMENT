
---

# Dynamic Web App Deployment


## Overview

The Dynamic Web App Deployment project demonstrates the creation and deployment of a web application with interactive features. This project involves building a web page with buttons that interact with backend services to display messages. The application is built using Java Servlets, Maven, Docker, and deployed on AWS.

## Features

- **Interactive Web Page**: Created with HTML, CSS, and JavaScript, featuring two buttons that fetch and display messages from the backend.
- **Backend Services**: Implemented using Java Servlets to handle requests and return messages in JSON format.
- **Build Automation**: Used Maven to package the project into a `.war` file for deployment on a Tomcat server.
- **Docker Containerization**: Deployed the application using Docker to ensure consistent operation across different environments.
- **Automated Deployment**: Utilized GitHub web hooks to automate the deployment process, facilitating streamlined updates and deployments.

## Technologies Used

- **HTML**: For creating the web page structure.
- **CSS**: For styling the web page.
- **JavaScript**: For adding interactivity to the web page.
- **Java Servlets**: For backend services and handling HTTP requests.
- **Maven**: For building the project and managing dependencies.
- **Docker**: For containerizing the application.
- **Tomcat**: For hosting the `.war` file.
- **AWS**: For deploying the Docker containers.
- **GitHub Web Hooks**: For automating deployments based on repository changes.

## Architecture

- **Frontend**: HTML, CSS, and JavaScript to create an interactive user interface.
- **Backend**: Java Servlets to process requests and return JSON responses.
- **Build Process**: Maven to create a `.war` file for deployment.
- **Containerization**: Docker for consistent deployment across environments.
- **Deployment**: AWS for hosting and managing Docker containers.

## Setup and Configuration

1. **Frontend Development**:
   - Develop the HTML, CSS, and JavaScript for the web page.
   - Implement button functionality to interact with backend services.

2. **Backend Development**:
   - Create Java Servlets to handle requests and return JSON data.
   - Configure Maven to build the project into a `.war` file.

3. **Docker Setup**:
   - Create a Dockerfile to containerize the application.
   - Build and test the Docker image locally.

4. **AWS Deployment**:
   - Deploy the Docker container to AWS, using EC2 instances or a container service.

5. **Automation with GitHub Web Hooks**:
   - Set up web hooks in GitHub to trigger deployment on code changes.

## Usage

1. **Push Changes to GitHub**:
   - The GitHub web hook will automatically detect changes and trigger a deployment.

2. **Monitor Deployment**:
   - Check Docker and AWS logs for deployment status and issues.

3. **Access the Web Application**:
   - Navigate to the provided AWS URL to interact with the deployed web app.

## Troubleshooting

- **Deployment Failures**: Review Docker and AWS logs for error messages.
- **Servlet Issues**: Debug Java Servlets and ensure correct JSON responses.
- **Frontend Problems**: Check browser console for JavaScript errors and network issues.

## Contact

For any questions or feedback, please contact [Ramesh Kanna G](mailto:rameshkanna841@gmail.com).

---
