# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


# ☁️ Bucket List Tracker

A serverless, cloud-backed web application that allows users to securely create, manage, and store personal bucket list goals using AWS Amplify.

This project was built as a hands-on exploration of modern cloud-native application development, combining frontend frameworks with managed AWS services to deliver a scalable, production-style architecture.

---

## ✨ Project Overview

The **Bucket List Tracker** enables authenticated users to:

- Sign up and log in securely
- Create and manage personal bucket list items
- Store goal data in the cloud
- Upload and associate files with each goal
- Access their data from anywhere through a hosted web interface

The application is fully serverless and designed to scale automatically without the need to manage infrastructure.

---

## 🧠 Architecture Summary

This application follows a **multi-tenant, serverless SaaS architecture**:

- **Frontend:** React hosted on AWS Amplify Hosting  
- **Authentication:** Amazon Cognito (via Amplify Auth)  
- **API:** AWS AppSync (GraphQL)  
- **Database:** Amazon DynamoDB  
- **Storage:** Amazon S3  

All backend services are provisioned and managed through **AWS Amplify**, enabling rapid development and deployment.

---

## 🏗️ Architecture Diagram

<img width="1607" height="731" alt="OTWXtfp3SRGIlQrsM0x6_A0" src="https://github.com/user-attachments/assets/9cbb23da-10c2-409d-af8e-5730ea60b070" />

---

## 🛠️ Technology Stack

- **Frontend:** React (Vite)
- **Backend & Deployment:** AWS Amplify
- **Authentication:** Amazon Cognito
- **API Layer:** AWS AppSync (GraphQL)
- **Database:** DynamoDB
- **File Storage:** Amazon S3
---

Here are the image badge links for your tech stack:
Frontend:

React: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
Vite: https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white

Backend & Deployment:

AWS Amplify: https://img.shields.io/badge/AWS_Amplify-FF9900?style=for-the-badge&logo=aws-amplify&logoColor=white

Authentication:

Amazon Cognito: https://img.shields.io/badge/Amazon_Cognito-DD344C?style=for-the-badge&logo=amazon-aws&logoColor=white

API Layer:

AWS AppSync: https://img.shields.io/badge/AWS_AppSync-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white
GraphQL: https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white

Database:

DynamoDB: https://img.shields.io/badge/Amazon_DynamoDB-4053D6?style=for-the-badge&logo=amazon-dynamodb&logoColor=white

File Storage:

Amazon S3: https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white

You can use these in markdown as:
markdown![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)Claude is AI and can make mistakes. Please double-check responses. Sonnet 4.5



## 🚀 Key Features

- Secure user authentication (sign up, sign in, sign out)
- Create, view, and delete bucket list items
- Cloud-based data persistence
- Optional file uploads per item
- Serverless, scalable backend
- Fully managed hosting and CI/CD via Amplify

---

## 🧩 Why This Project

This project was built to:

- Gain hands-on experience with AWS serverless services
- Understand end-to-end cloud application workflows
- Practice integrating authentication, APIs, databases, and storage
- Demonstrate real-world cloud architecture principles

It reflects how modern SaaS applications are commonly built on AWS today.

---

## 🧪 Local Development

```bash
npm install
npm run dev
