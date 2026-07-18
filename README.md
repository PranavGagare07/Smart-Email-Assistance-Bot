# 📧 Smart Email Assistant

> An AI-powered email generation application that helps users create professional, personalized, and context-aware emails instantly using **Google Gemini API**.

![Java](https://img.shields.io/badge/Java-17-orange?logo=openjdk)
![Spring Boot](https://img.shields.io/badge/SpringBoot-Backend-6DB33F?logo=springboot)
![HTML](https://img.shields.io/badge/HTML5-Frontend-E34F26?logo=html5)
![CSS](https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css3)
![Gemini API](https://img.shields.io/badge/Google-Gemini%20API-4285F4?logo=google)

---

# 📌 Overview

**Smart Email Assistant** is an AI-powered web application that enables users to generate well-structured, personalized emails within seconds. Powered by the **Google Gemini API**, the application understands user prompts and creates emails in multiple writing styles, making professional communication faster and more effective.

Whether it's a formal business email, a friendly follow-up, or a casual message, Smart Email Assistant delivers high-quality content with minimal effort.

---

# ✨ Features

- 🤖 AI-powered email generation using Google Gemini API
- ✍️ Multiple email tones
  - Formal
  - Professional
  - Casual
  - Friendly
- ⚡ Instant email generation
- 🎯 User-friendly interface
- 📱 Fully responsive design
- 🔄 Fast backend processing with Spring Boot
- ☁️ Cloud deployment support
- 📋 One-click copy generated email
- 📝 Clean and structured email formatting

---

# 🛠 Tech Stack

## Frontend

- HTML5
- CSS3

## Backend

- Java
- Spring Boot
- Spring Web
- REST APIs

## AI Integration

- Google Gemini API

## Deployment

- Railway
- Render

---

# 🏗 System Architecture

```
              User
                │
                ▼
      HTML + CSS + JavaScript
                │
         REST API Request
                │
                ▼
        Spring Boot Backend
                │
                ▼
        Google Gemini API
                │
                ▼
      AI Generated Email
                │
                ▼
        Display to User
```

---

# 🚀 Workflow

1. User enters the email topic or prompt.
2. User selects the desired email tone.
3. Frontend sends the request to the Spring Boot backend.
4. Backend communicates with the Google Gemini API.
5. AI generates a complete email.
6. Generated email is displayed instantly.
7. User can copy and use the email.

---

# 📂 Project Structure

```
Smart-Email-Assistant/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   ├── resources/
│   │   └── static/
│   │
│   └── test/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── screenshots/
│
├── pom.xml
│
├── README.md
│
└── .gitignore
```

---

# ⚙ Installation

## Clone the Repository

```bash
git clone https://github.com/yourusername/Smart-Email-Assistant.git

cd Smart-Email-Assistant
```

---

## Configure Gemini API

Create an `application.properties` file inside:

```
src/main/resources/
```

Add your Gemini API Key:

```properties
gemini.api.key=YOUR_API_KEY
```

---

## Run the Backend

```bash
./mvnw spring-boot:run
```

or

```bash
mvn spring-boot:run
```

---

## Open the Application

```
http://localhost:8080
```

---

# 📸 Screenshots

> Add screenshots of your application here.

### Home Page

```
screenshots/home.png
```

### Email Generation

```
screenshots/generate.png
```

### Generated Output

```
screenshots/output.png
```

---

# 💡 Example

### Input

```
Write a professional email requesting leave for two days due to illness.
```

### Tone

```
Professional
```

### Output

```
Subject: Leave Request for Medical Reasons

Dear Manager,

I hope you are doing well.

I would like to request leave for two days due to illness. I am currently not feeling well and need time to recover. I will ensure that all pending tasks are completed or properly handed over before my leave.

Thank you for your understanding.

Kind regards,
Your Name
```

---

# 📈 Future Enhancements

- 📧 Email templates
- 🌍 Multi-language support
- 🎙 Voice-to-email generation
- 📄 PDF export
- 📨 Direct Gmail integration
- 📌 Email history
- 🎯 Grammar and spell checking
- 😊 Emotion-aware tone suggestions
- 🌙 Dark mode
- 🔐 User authentication

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
