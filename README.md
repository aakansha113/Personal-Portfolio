# Personal Portfolio Website(Docker + nginx)
A minimalist, Dockerized personal portfolio site using Nginx (Alpine image) for high performance and easy deployment.

## Features

🎨 Modern UI — Clean, minimal, and responsive design

🐳 Dockerized — Run your portfolio anywhere with one command

☁️ DevOps-focused — Highlights tools like AWS, Docker, Kubernetes, Terraform, Git

💼 Project Sections — Showcases my DevOps and cloud projects

📬 Contact Section — LinkedIn + Gmail icons

⚡ Fast & lightweight (no frameworks)

##  📁 Folder Structure
```
my-portfolio/
│── index.html
│── style.css
│── script.js
│── Dockerfile
│── .gitignore
│── .dockerignore
│──assets/
|    ├── linkedin.svg
│    ├── avtar.jpg
│── icons/
│    ├── c.svg
│    ├── python.svg
│    ├── git.svg
│    ├── github.svg
│    ├── terraform.svg
│    ├── kubernetes.svg
│    ├── docker.svg
│    ├── aws.svg
│    ├── gmail.svg
│    ├── linux.svg
│           
```
## Dockerfile Overview

- Uses `nginx:alpine` as the base image
- Removes default Nginx HTML files
- Copies your website files into Nginx's root HTML directory
- Exposes port 80
- Runs Nginx in the foreground
  
## 📥 Clone This Repository

To clone this portfolio on your local system, run:
```
git clone https://github.com/aakansha113/Personal-Portfolio.git
```
## Getting Started
### 🐳 Docker Setup:

#### Build the Docker Image
```
docker build -t my-portfolio .
```

#### Run the Container
```
docker run -p 8080:80 my-portfolio
```

#### Now open:

```
http://localhost:8080
```

### 🛠️ Technologies Used

1-HTML5

2-CSS3

3-JavaScript

4-Docker

### ⭐ Show Your Support

#### If you like this portfolio, feel free to ⭐ star the repo!


