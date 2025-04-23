# 🏛️ LokDharma

**LokDharma** is a community-driven web application that allows users to **anonymously report civic issues** in their cities. From broken roadways to government corruption, users can share their stories and draw attention to problems that impact everyday life.

Verified users in the community can **authenticate or challenge** the validity of these posts, encouraging **transparency and civic responsibility** across India.

---

## 🚀 Vision

To empower citizens of India by giving them a digital voice to highlight civic issues and hold local authorities accountable in a transparent, community-led manner.

---

## 📦 Microservices Architecture

LokDharma follows a microservices architecture to ensure scalability, maintainability, and independent development of services.

### ✅ 1. JanAwaz (Post Service)

Handles the **creation of posts** (called *JanAwaz*), which are appeals from citizens to the government or authorities. Each post contains:

- **Title**: Summary of the issue
- **Content**: Detailed description
- **Tags**: For categorization (e.g. #government, #municipal)
- **Truth Count**: Number of users who support the authenticity of the issue
- **False Count**: Number of users who dispute the issue
- **Truth Rate**: A percentage based on community validation
- **Comment **: People add comments as well
- Github repo link: **https://github.com/Vivekkr0311/JanAwaz.git** (It is a private repo for now. If you would like to see it, drop me a message and I will explain the code over a call.)

#### 📌 Example

```text
Title: Broken Road in front of ABC Public School  
Content: It's been more than a year since the people of XYZ city requested the municipal corporation to fix this road, but it hasn't been addressed yet. This is a humble request to the government to please fix it as soon as possible.  
Tags: #government #municipal corporation  
Truth: 500, False: 1, Truth Rate: 99%
```

---

### 🔒 2. User Microservice *(Planned)*

Will handle:

- User registration
- User profiles
- Verification mechanisms

---

### 🔐 3. Authorization Service *(Planned)*

Will manage:

- Login & Authentication (JWT/OAuth)
- Role-based Access Control (RBAC)
- Token management

---

### 🧭 4. Eureka Server 

For **service discovery** and registry of microservices.
Currently under developement.
- Github repo link: **https://github.com/Vivekkr0311/EurekaServer_LokDharma.git**
---

### 🚪 5. Gateway Server

- Route requests to appropriate microservices
- Handle cross-cutting concerns (e.g., logging, rate limiting, security)
- Girhub repo link: **https://github.com/Vivekkr0311/LokDharma_Gateway.git**

---

## 🔧 Future Development

- 💬 Comment and discussion feature on each post
- 📍 Geo-tagging of issues
- 📊 Admin dashboard with reports & analytics
- 📱 Mobile-friendly UI
- 🔁 Integration with social media for sharing

---

## 🛠️ Tech Stack (Planned)

- Java + Spring Boot (Microservices)
- Spring Cloud (Gateway, Eureka)
- MongoDB / PostgreSQL 
- React / Angular (Frontend)
- Docker + Kubernetes (Deployment)
- Jenkins / GitHub Actions (CI/CD)
- SonarCloud

---

## 📣 This is just the beginning...

LokDharma is a passion project aimed at real change. More features and services will be developed step by step. Contributions, feedback, and ideas are most welcome.

---

## 📬 Contact

For suggestions or collaboration, reach out at: **vivekkr0311@gmail.com**
