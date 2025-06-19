# Building DevOps Foundations: Jenkins-Powered CI/CD Pipeline

[![Netlify Status](https://api.netlify.com/api/v1/badges/ef030ef9-54ed-44d9-8e78-18550b8c2034/deploy-status)](https://app.netlify.com/projects/reliable-torte-876769/deploys)

This project demonstrates a complete Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins, Docker, GitHub, and Netlify.

## 📦 Tech Stack

- **Jenkins**: Automates the build, test, and deploy process
- **Docker**: Provides isolated, repeatable build environments
- **Netlify CLI**: Handles production deployment via CLI
- **Node.js & npm**: Project runtime and dependency management
- **JUnit**: Test reporting and result tracking
- **GitHub**: Source control and project repository

## 🚀 What This Project Does

- Clones a React project from GitHub
- Runs inside Docker containers with consistent environments
- Installs dependencies and builds the application
- Runs project tests and generates JUnit reports
- Deploys automatically to Netlify using environment-secured credentials

## 🔐 Environment Variables

To deploy via Netlify CLI, the following environment variables are securely configured in Jenkins:

- `NETLIFY_AUTH_TOKEN`
- `NETLIFY_SITE_ID`

## ✅ Status

Each build and deploy is tracked through Jenkins pipelines and reflected by the live Netlify status badge above.

## 🖼️ Images

### Pipeline
![Jenkins Pipeline](https://github.com/user-attachments/assets/9afece67-cb68-414c-a235-9b9de5a38823)

### Successful builds in Jenkins
![Build via jenkins](https://github.com/user-attachments/assets/9a0e1735-1c9c-4726-a97c-ee4358bfd2ef)

### Netlify Deployment confirmation
![Netlify Auto deployment](https://github.com/user-attachments/assets/0b10a874-d010-4785-bc2e-6f6508a58e8a)

### Final stage/production 
![Deployment](https://github.com/user-attachments/assets/5f4eb21f-f933-43bf-ae2c-12fe128cbd43)

See the site here: https://reliable-torte-876769.netlify.app/


## 🧠 Course Credit

This project was built as part of a complete Jenkins CI/CD tutorial by **TechWorld with Nana** on [YouTube](https://www.youtube.com/watch?v=soIpt3c7tVE).

---

## 🎨 Profile

- ✨ **Génesis M. Ojeda**
  - 🐙 **GitHub**: [DevQueenPR](https://github.com/DevQueenPR)  
  - 💼 **LinkedIn**: [Génesis M. Ojeda](https://www.linkedin.com/in/g%C3%A9nesis-ojeda-451576302?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)  
