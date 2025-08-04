# DevOps Internship Project: CI/CD for Web App Deployment

This repository showcases my practical understanding of CI/CD by automating the deployment of a simple Node.js web application using GitHub Actions.

## ✨ What I've Done

  * **Developed a Basic Node.js Web App:** Created a minimal HTTP server in `index.js`.
  * **Containerized the Application:** Wrote a `Dockerfile` to package the Node.js app into a Docker image.
  * **Implemented a GitHub Actions CI/CD Pipeline:** Configured `main.yml` to automatically:
      * Build the Node.js application.
      * Build a Docker image from the application.
      * Push the Docker image to Docker Hub.
  * **Secured Credentials:** Utilized GitHub Secrets to securely store and access Docker Hub credentials within the CI/CD pipeline.

## 🚀 Technologies Used

  * **Node.js**
  * **Docker**
  * **GitHub Actions**
  * **Docker Hub**

## 📂 Repository Structure

```
.
├── .github/workflows/main.yml  # CI/CD pipeline definition
├── Dockerfile                  # Docker image instructions
├── index.js                    # The web application code
├── package.json                # Node.js dependencies
└── README.md                   # This file
```

## ✅ Result

Successfully demonstrated automated build, containerization, and pushing of a web application to Docker Hub via a GitHub Actions CI/CD pipeline on every push to the `main` branch.

-----
