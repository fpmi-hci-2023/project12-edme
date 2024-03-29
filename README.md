## EDME Tutoring center
This application is an MLP-version of a website for an educational center. It
covers the most common scenarios of user-interaction and provides basic usability
means. The application is designed to help parents that seek additional education
for their children.  It is avalible both as Android and web application.

## Features
- Log-in interface
- Menu of cources and tutors with full description
- Communication with tutors
- Convenient registration for classes
- Viewing student progress. 
- Contats and reference information

## Technologies used
- Spring Boot: A powerful and flexible Java framework for building web applications.
- Thymeleaf: A modern server-side Java template engine for web and standalone
environments.
- Hibernate: An object-relational mapping framework for the Java programming
language.
- OkHttp: An open-source HTTP client for Java that simplifies communication with
APIs.

## Getting started
### Android
- Download Git and Android Studio
- Using Git Bash write `git init`
- Clone repository with `git clone https://github.com/fpmi-hci-2023/project12a-mobile-edme`
- Compile & execute project using Android Studio

### Web application
- Clone repository with `git clone https://github.com/Antonio205/edme-pmms.git`
- Navigate to the project directory
- Deploy web application using docker build command: docker build -t project12-edme
- Launch the application using prefferd port: docker run -p 8000:80 project12-edme
- Access the application in a browser

## Contributing
Andrievskiy Maksim - documentation, frontend development, usability tests

Tretyakov Dmitry - market research, informational architecture, context scenarios, visual design, check-list tests, CI/CD, Swagger

Kurochkin Aleksandr -  audience-research, KJ diagrams, informational arhictecture, visual design, development of an interactive prototype, Deployment on Heroku, tests with SonarCloud

Yminskiy Anton - Team Lead, Github Projects, informational architecture, Android application development, progress reports

Temnyakov Yan - Github Actions for Docker containers, local deployment with docker, application backend development
