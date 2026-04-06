# 🚀 Maven Jenkins CI/CD Project

This project demonstrates a complete **CI/CD pipeline** using Jenkins integrated with a Maven-based Java application.

---

## 🔄 CI/CD Flow

GitHub → Jenkins → Maven Build → Test → Deploy

---

## ⚙️ Jenkins Configuration

### 🔹 Build Steps (Maven)

![Build Steps](screenshots/build-steps.png)

### 🔹 Post Build Actions

![Post Build Actions](screenshots/post-build-actions.png)

---

## 📸 Project Screenshots

### 🔹 Jenkins Dashboard

![Jenkins Dashboard](screenshots/jenkins-dashboard.png)

### 🔹 Build Success

![Build Success](screenshots/build-success.png)

### 🔹 Console Output

![Console Output](screenshots/console-output.png)

### 🔹 File Location

![File Location](screenshots/file-location.png)

---

## 🛠️ Tech Stack

* Java
* Maven
* Jenkins
* GitHub
* Linux (CentOS)

---

## ✨ Features

* Automated build using Maven
* Continuous Integration using Jenkins
* Test execution and reporting
* Artifact generation (.jar file)
* Deployment using shell script

---

## 📦 Build Commands Used

```bash
mvn clean package
mvn test
```

---

## 🚀 Deployment Command

```bash
java -jar target/my-app-1.0-SNAPSHOT.jar
```

---

## 👨‍💻 Author

**Vishal Ranga**

* MCA Student | Cloud & DevOps Enthusiast
* Skills: AWS, Linux, IAM, Terraform, Docker

---

## 📌 Project Highlights

* Implemented a real-world CI/CD pipeline
* Integrated GitHub with Jenkins
* Automated build, test, and deployment process
* Hands-on experience with DevOps tools

---

## ⭐ Future Improvements

* Add Docker containerization
* Deploy application on AWS
* Convert to Jenkins Pipeline (Jenkinsfile)
* Add monitoring (Prometheus + Grafana)

---
