# Joshua Agyekum - Professional Portfolio

A responsive portfolio website showcasing DevOps and Systems Administration expertise, deployed on AWS ECS with automated CI/CD.

## 🚀 Live Demo
Portfolio website showcasing professional skills, certifications, and achievements.

## 🛠️ Tech Stack
- **Frontend**: HTML5, Bootstrap 5, JavaScript
- **Containerization**: Docker (nginx:alpine)
- **Cloud**: AWS ECS Fargate, ECR
- **CI/CD**: GitHub Actions
- **Monitoring**: AWS CloudWatch

## 📋 Features
- Responsive design with mobile optimization
- Professional certifications carousel (31+ certificates)
- Skills categorization with tabbed interface
- Achievement metrics and project highlights
- Contact form with Google Maps integration
- Social media integration (LinkedIn, GitHub, Credly)

## 🏗️ Architecture
```
GitHub → GitHub Actions → AWS ECR → AWS ECS Fargate
```

## 🚀 Quick Start

### Local Development
```bash
# Clone repository
git clone <repository-url>
cd joo-kofi

# Run with Docker
docker build -t portfolio .
docker run -p 8080:80 portfolio
```

### Deployment
Automated deployment via GitHub Actions on push to `main` branch:
1. Builds Docker image
2. Pushes to AWS ECR
3. Updates ECS service

## 📁 Project Structure
```
├── css/                 # Stylesheets
├── js/                  # JavaScript files
├── images/              # Images and certificates
├── .github/workflows/   # CI/CD pipeline
├── Dockerfile          # Container configuration
├── index.html          # Main portfolio page
└── task.json           # ECS task definition
```

## 🔧 Configuration
- **AWS Region**: eu-north-1
- **Container**: 1024 CPU, 3072MB memory
- **Port**: 80 (HTTP)

## 📞 Contact
- **Email**: joshuaagyekum21@gmail.com
- **Phone**: 46399384
- **Location**: Oslo, Norway
- **LinkedIn**: [Profile](https://www.linkedin.com/public-profile/settings?trk=d_flagship3_profile_self_view_public_profile)
- **GitHub**: [kofijoo](https://github.com/kofijoo)
- **Certifications**: [Credly Portfolio](https://www.credly.com/users/joshua-agyekum.7b55a7d0/edit#badge-portfolio)

## 📄 License
© 2024 Joshua Agyekum. All rights reserved.