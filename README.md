# DevOps CI/CD Project 🚀

This project demonstrates a complete DevOps pipeline:
- **GitHub** for source code management
- **Jenkins** for CI/CD automation
- **Docker** for containerization
- **AWS EC2 (Linux)** for deployment

## Steps
1. Push code to GitHub
2. Jenkins pipeline builds & tests
3. Docker image created
4. Deploy to EC2 instance

## How to Run
```bash
docker build -t devops-app .
docker run -d -p 3000:3000 devops-app

