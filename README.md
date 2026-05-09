# AI Vision Cloud Image Recognition System

A cloud-based intelligent image recognition web application built using Microsoft Azure services and Vanilla JavaScript.

## Project Overview

This project demonstrates how cloud computing and AI services can be integrated to create a scalable and cost-efficient image analysis system.

The application allows users to upload an image through a web interface. The uploaded image is stored in Azure Blob Storage, processed using Azure AI Vision services, and the generated natural language description is displayed back to the user.

Example:

Input Image: Dog photo

Generated Output:
"A dog with a person's arm"

---

## Technologies Used

### Cloud Services
- Microsoft Azure
- Azure Functions
- Azure Blob Storage
- Azure Table Storage
- Azure AI Vision

### Frontend
- HTML5
- CSS3
- Vanilla JavaScript

### Development Tools
- Visual Studio Code
- Live Server Extension

---

## Features

- Image Upload Interface
- Real-time Cloud Processing
- AI-based Image Caption Generation
- Azure Blob Storage Integration
- Azure Table Storage Polling
- Simple and Lightweight UI
- No External Libraries Used

---

## System Workflow

1. User uploads an image.
2. Image is uploaded to Azure Blob Storage.
3. Azure Function gets triggered.
4. Azure AI Vision analyzes the image.
5. Natural language description is generated.
6. Result is stored in Azure Table Storage.
7. Frontend fetches and displays the result.

---

## Project Structure

```bash
project-folder/
│
├── index.html
└── README.md
````

---

## How to Run the Project

1. Download or clone the repository.
2. Open the project folder in Visual Studio Code.
3. Install the Live Server extension.
4. Run `index.html` using Live Server.
5. Upload an image and wait for AI analysis.

---

## Output Example

System Status:

* 🚀 Uploading to Blob
* 🧠 AI is thinking
* ✅ Analysis Complete

Generated Result:
"Result: a dog with a person's arm"

---

## Future Enhancements

* User authentication
* Multiple image support
* Image history tracking
* Better UI/UX design
* Support for video analysis
* Mobile responsive interface

---

## Author

Developed as a cloud computing and AI integration academic project using Microsoft Azure services.

```
