# Modern Web Applications Course - Lab Da1 

![image](https://github.com/user-attachments/assets/d339e47b-7db9-4c47-82f6-bf1f6ac88af2)


## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup](#setup)
- [Usage](#usage)
- [Pages Overview](#pages-overview)
- [Conclusion](#conclusion)

## Introduction

This project is a static web application developed for a university hackathon registration system. The system includes six pages: Landing Page, Registration Form Page, Confirmation Page, Contact Page, Team Formation Page, and Fee Calculator Page. The application is designed to be user-friendly and visually appealing, utilizing a consistent mauve color scheme across all pages.

## Features

- **Landing Page**: Provides an overview of the hackathon with navigation links to other pages.
- **Registration Form Page**: Allows users to register for the hackathon by filling out a form.
- **Confirmation Page**: Displays a confirmation message and the registration details.
- **Contact Page**: Provides a contact form for users to reach out with any questions or concerns.
- **Team Formation Page**: Allows users to form teams and dynamically updates the team summary.
- **Fee Calculator Page**: Calculates the registration fee based on the number of participants and their types.

## Technologies Used

- **HTML5**: For structuring the content.
- **CSS3**: For styling the web pages and maintaining a consistent look and feel.
- **JavaScript**: For adding dynamic functionality to the Team Formation and Fee Calculator pages.

## Project Structure

```
hackathon-registration-system/
│
├── index.html               # Landing Page
├── register.html            # Registration Form Page
├── confirmation.html        # Confirmation Page
├── contact.html             # Contact Page
├── team_formation.html      # Team Formation Page
├── fee.html                 # Fee Calculator Page
├── styles.css               # Common CSS file for all pages
├── hackathon.jpg            # Image used on the Landing Page
└── README.md                # Project README file
```

## Setup

To set up this project locally, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/hackathon-registration-system.git
   ```
2. **Navigate to the project directory:**
   ```sh
   cd hackathon-registration-system
   ```

3. **Open the HTML files in a web browser:**
   Simply double-click the HTML files (e.g., `index.html`) or open them with a web server.

## Usage

- Open `index.html` in a web browser to access the Landing Page.
- Use the navigation links to access the Registration Form, Contact Page, Team Formation Page, and Fee Calculator Page.
- Fill out the forms on each page to test the functionality.

## Pages Overview

### Landing Page (`index.html`)
- Contains a header, navigation links, hackathon details, and an image.

### Registration Form Page (`register.html`)
- Includes a form with fields for Name, Email, Phone Number, Skill Set, Level of Experience, and Terms and Conditions checkbox.

### Confirmation Page (`confirmation.html`)
- Displays a confirmation message and the details entered in the registration form.

### Contact Page (`contact.html`)
- Contains a form for users to submit their Name, Email, and Message.

### Team Formation Page (`team_formation.html`)
- Allows users to enter team details and dynamically updates the team summary based on input fields.

### Fee Calculator Page (`fee.html`)
- Calculates and displays the total fee based on the number of participants and their types.

## Conclusion

The University Hackathon Registration System is a static web application designed to provide a seamless and user-friendly registration experience for a university hackathon event. By utilizing HTML, CSS, and JavaScript, the application offers a consistent and dynamic interface that meets the needs of both organizers and participants. This project serves as an excellent example of front-end web development techniques and best practices.

