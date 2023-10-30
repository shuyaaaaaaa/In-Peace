# InPeace :peace_symbol:

InPeace is designed to bring serenity to the bustling streets of Manhattan. Tailored for introverts seeking quieter spots, our app leverages a predictive model to guide users to less crowded places. Beyond its pathfinding feature, InPeace serves as a community platform where users can engage with posts through likes, comments, and more.

## Table of Contents
- [Features](#features)
- [Architecture](#architecture)
- [Tech Stack](#tech-stack)
- [Media](#media)

## Features
- **Place Finder**: Predicts and guides users to less busy locations based on our advanced prediction model.
- **Route Guidance**: Directs users from Point A to B while avoiding bustling areas.
- **Community Platform**: A space for users to post, like, comment, and delete entries, building a like-minded community.
- **Authentication**: Equipped with secure login and sign-in functionalities.

## Architecture
![InPeace Architecture](https://user-images.githubusercontent.com/123382891/279217248-4151670d-0fb8-4537-9fbb-43ef3104490d.png)

The app's structure is based on microservices architecture, each hosted in Docker containers, all orchestrated through an API Gateway. Here's a breakdown:

- **UI Layer**: Built with React.js, responsible for the visual interface and user interactions.
- **Backend Layer**: Houses multiple services such as:
  - Map
  - Machine Learning Predictions
  - Places Database
  - User Management and Authentication
  - Community Features
- **Data Layer**: Uses a PostgreSQL database hosted on AWS, with backups and redundancy managed through database copies.

## Tech Stack
- **Frontend**: React.js
- **Backend**: Flask, Spring Boot
- **Database**: PostgreSQL on AWS
- **Containerization**: Docker
- **Hosting**: AWS EC2

## Media
- **[InPeace App Walkthrough Video](https://github.com/shuyaaaaaaa/InPeace/assets/123382891/ed6b7b60-0496-4a0f-8566-6d2a0fb9deb2)**
- **Images**:  
  - ![Image Description](https://user-images.githubusercontent.com/123382891/279217358-9fb0f86f-3b2a-478f-a1a8-e0655d6eff4d.png)  
  - ![Image Description](https://user-images.githubusercontent.com/123382891/279217377-f550c5ef-078e-44ba-9f0b-4c2589fce17f.png)
  - ![Image Description](https://user-images.githubusercontent.com/123382891/279217389-a9b359d2-3438-4c85-818a-3fb6305667c9.png)
  - ![Image Description](https://user-images.githubusercontent.com/123382891/279217397-b05afebf-6121-45b6-ad47-063994757c96.png)
  - ![Image Description](https://user-images.githubusercontent.com/123382891/279217404-4d131be6-a5af-4d47-8fc2-6ba74c7b85bd.png)

## :mailbox: Feedback & Contributions

Love the app? Found a bug? Have suggestions? Feel free to contribute or provide feedback! Your input is valued and helps improve the experience for everyone.
