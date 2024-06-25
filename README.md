# URL Shortener Application

## Overview
This is a dynamic URL shortener application designed to provide users with the ability to generate shortened URLs. The application features user authentication for signup and login, ensuring secure access and personalized experiences. Additionally, users can track the number of clicks or usage of their shortened URLs.

## Features
- **User Authentication**: Secure signup and login functionality to ensure only authorized users can create and manage shortened URLs.
- **URL Shortening**: Generate shortened URLs for any given long URL.
- **Click Tracking**: Track the number of clicks or usage for each shortened URL.
- **Personalized Dashboard**: Each user has access to a personalized dashboard displaying their shortened URLs and usage statistics.

## Getting Started

### Prerequisites
- Node.js
- MongoDB

## Usage

### Signup and Login
- Users need to sign up to create an account. After signing up, they can log in using their credentials.

### Creating a Shortened URL
- Once logged in, users can enter a long URL in the input field on their dashboard and click the "Shorten" button to generate a shortened URL.

### Tracking URL Usage
- The dashboard displays a list of all shortened URLs created by the user, along with the number of clicks each URL has received.

## Technologies Used
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Frontend**: HTML, CSS, JavaScript
