# GateSync - QR Code Generator & Decoder

## 🚀 Overview
GateSync is a Spring Boot-based web application that generates and decodes QR codes in real time using structured data formats such as URLs, emails, phone numbers, and more.

## 🛠 Tech Stack
- Java
- Spring Boot
- Thymeleaf
- ZXing (QR processing)

## ✨ Features
- Generate QR codes for multiple data types
- Decode QR codes from images
- Clean layered architecture (Controller, Service, Model, Parser)

## 🧠 Architecture
- Controller Layer → Handles HTTP requests
- Service Layer → QR encoding/decoding logic
- Model Classes → Data structures
- Parser Classes → Format conversion

## ❌ Database
This project does not use a database. It processes data in real time.

## ▶️ Run Locally
1. Clone the repo
2. Open in IDE
3. Run `SpringBootQrcodeGeneratorApplication.java`
4. Open `http://localhost:8080`
