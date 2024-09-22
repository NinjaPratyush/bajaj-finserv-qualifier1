# BFHL Project- By Pratyush Kumar(RA2111003010146)

A project for the Online Test of Bajaj Finserv, where we are required to develop a full-stack solution that processes JSON input, differentiating between Characters, Numbers, and the Highest Alphabet in the input.

 ### Project Link: https://ninjapratyush.github.io/bajaj-finserv-qualifier1/ 

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Backend Setup](#backend-setup)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)

## Project Overview

This project consists of two main components:
1. *Backend (API)*: A REST API with one endpoint /bfhl that accepts both GET and POST methods. The API processes input JSON data and returns the required response.
2. *Frontend*: A web interface that accepts JSON input from the user, sends it to the API, and displays the filtered response based on a multi-select dropdown.

## Features

### Backend
- Accepts POST requests containing an array of data and a base64-encoded file.
- Returns user details, a breakdown of numbers, alphabets, the highest lowercase alphabet, and file metadata.
- Provides a hardcoded response for GET requests.

### Frontend
- Allows the user to input JSON data via a text field.
- Displays results based on the selected filters (Numbers, Alphabets, Highest Lowercase Alphabet) in a dropdown.

## Backend Setup

### Prerequisites
- Python 3.8+
- Flask
- Gunicorn (for deployment)

## Technologies Used

- Backend: Python, Flask, Gunicorn
- Frontend: React.js
- Hosting: Heroku (Backend), Vercel/Netlify (Frontend)
## Future Enhancements
- We can implement a robust authentication mechanism for users.
- We can add more features like pagination and filtering of results.
- We can improve error handling for invalid requests and unsupported file types.
