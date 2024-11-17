# Mobile Application Development Course Repository

## Introduction

This repository contains the code for the Mobile Application Development course, which includes various exercises and projects focused on Android app development. It covers fundamental concepts of Android, database handling, UI design, and implementing Machine Learning and Deep Learning techniques in mobile apps.

## List of Experiments

### 1. Introduction to Android Development
- **Overview**: About Android, prerequisites for learning Android, Dalvik Virtual Machine, .apk file extension, and Android API levels (versions & version names).
- **Concepts Covered**:
  - Android Java basics
  - Project folder structure
  - Simple programming and running an Android project
  - Generating build/APK from Android Studio

### 2. Font and Color Change Application
- **Objective**: Develop an application to change the font and color of the text and display a toast message when the user presses a button.

### 3. Scientific Calculator
- **Objective**: Develop a scientific calculator to perform arithmetic and mathematical functions using the `Math` class.
- **Functions**: Addition, multiplication, division, cos, sin, tan, power, square root, log, natural log, mod.

### 4. SQLite Database Operations
- **Objective**: Create a database table with the following structure: `Student (Name, Roll No, Marks)`. Implement Android operations to:
  - Insert student details
  - Update the student record
  - Delete a specified record and view the details.

### 5. User Validation Form
- **Objective**: Design an activity with two text boxes where the user can enter a username and ID. Validate the fields with the following checks:
  - Both fields should not be empty
  - Name field should have only alphabets
  - ID field should have numeric values (only 4 digits)

### 6. Machine Learning-based Application
- **Objective**: Develop an Android application that:
  - Converts text to speech
  - Converts speech to text

### 7. OCR-based Road Sign Recognition
- **Objective**: Develop an application to read OCR from road signs using Deep Learning techniques.

### 8. Image Capture and Display
- **Objective**: Develop an Android application to capture an image using the camera and display it using an `ImageView`.

### 9. Barcode Scanning App
- **Objective**: Develop an Android app for scanning barcodes using Deep Learning.

### 10. **Emotibot Project**
- **Objective**: Develop an interactive chatbot application where the user can interact with **Emotibot**—an AI-powered bot that provides responses based on input. The bot fetches responses from an API and maintains a conversation history. This chatbot app can be used as an assistant, allowing users to ask questions and receive appropriate answers.

### Features:
- **User Input**: The user can type a question or statement.
- **Emotibot Response**: The app sends the input to an API (hosted on a server) that processes the input and provides a response.
- **Conversation History**: All interactions are stored in a conversation history, allowing the user to view past interactions with Emotibot.
- **UI Design**: A simple and clean interface that distinguishes between user messages and bot responses using different message styles.

## Technologies Used

- **Programming Languages**: Kotlin, Java
- **Development Tools**: Android Studio, OkHttp
- **Machine Learning/Deep Learning**: TensorFlow, PyTorch (for Deep Learning models like OCR, image recognition)
- **Libraries**: OkHttp, SQLite, TextToSpeech, SpeechToText

## Emotibot: Detailed Information

### Overview
**Emotibot** is a conversational AI bot built with the ability to engage in real-time dialogue with users. The app leverages an API to get responses from a machine learning model, enabling the bot to understand and reply intelligently to text inputs.

#### Key Features of Emotibot:
1. **User Interaction**: Users can type messages or questions to interact with the bot.
2. **API Integration**: Emotibot communicates with a server-based API to fetch and display responses to user inputs.
3. **Conversation Management**: The app keeps track of all messages exchanged between the user and the bot, ensuring context is maintained.
4. **Dynamic UI**: The user interface differentiates between user and bot responses using distinct visual styles.

#### Technical Details:
- **API Endpoint**: The app connects to the backend API hosted on the server (e.g., `https://your-api-endpoint.com`). The server is responsible for processing the user input and generating bot responses.
- **Backend Logic**: The bot uses a pre-trained machine learning model that processes the user’s query and produces a suitable response.
- **Conversation History**: The chat interface displays the entire history of messages exchanged between the user and the bot, making the conversation flow more natural.
  
#### User Interface:
- The app has a **TextInputEditText** for the user to enter messages and a **ScrollView** to display the conversation.
- User messages are aligned to the left, and bot responses are aligned to the right, making the conversation easier to follow.
- Each message is shown with background colors to distinguish between user and bot messages.

### How to Run Emotibot

#### Step 1: Clone the repository
Start by cloning the repository to your local machine:
```bash
git clone https://github.com/yourusername/your-repository-name.git
