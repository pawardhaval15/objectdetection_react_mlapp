# Real-Time Object Detection Using React and TensorFlow.js with COCO-SSD

This project is a real-time object detection application built using React and TensorFlow.js, leveraging the COCO-SSD model. It detects objects using the user's webcam feed and identifies them in real time.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the App](#running-the-app)
- [App Structure](#app-structure)
- [References](#references)

## Introduction

This app uses TensorFlow.js and the COCO-SSD pre-trained model to detect and classify objects from the webcam. It's a web-based solution for real-time object detection using a modern, React-based frontend and runs entirely in the browser.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **TensorFlow.js**: A library to run machine learning models in the browser.
- **COCO-SSD**: A pre-trained object detection model trained on the COCO dataset, recognizing 80 object classes.
- **Vite**: A fast build tool for modern web applications.

## Features

- Real-time object detection via webcam.
- Detects and labels multiple objects with confidence scores.
- Displays bounding boxes around detected objects.
- Lists all detected objects in real time.

## Prerequisites

- Node.js (>= 14.x)
- npm or yarn
- A webcam for real-time detection

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/react-tfjs-object-detection.git
   cd react-tfjs-object-detection
   
2. Install dependencies:
   ```bash
   npm install
   
3. Install TensorFlow.js and COCO-SSD:
   ```bash
   npm install @tensorflow/tfjs @tensorflow-models/coco-ssd

## Running the App

1. Start the app:
   ```bash
   npm run dev
   
2. Open your browser at http://localhost:3000 and allow webcam access.

3. Object detection starts automatically, showing bounding boxes and labels around detected objects.

[Visit My Website](https://react-mlapp.vercel.app/)

