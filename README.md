# AirBnB Clone Project

## Overview
This project is a clone of the AirBnB web application. It aims to replicate the core functionalities of the original platform, such as user registration, listing accommodations, booking stays, and managing reviews.

## Project Goals
- Learn and apply web development principles
- Implement full-stack features from scratch
- Practice team collaboration with Git and GitHub

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Express And NodeJS
- **Database**: MySQL
- **Version Control**: Git & GitHub


🧠 UI/UX Design Planning
🎯 Design Goals
Create a clean, intuitive, and responsive interface

Ensure a seamless booking experience for all users

Prioritize accessibility and mobile-friendliness

Minimize user effort by reducing steps and friction points

Align visuals with modern web application aesthetics

🔑 Key Features to Implement
Search and filter for available properties

View property listings with images and pricing

Access detailed descriptions and reviews for each listing

Simple and secure booking process

User authentication (sign-up, login, logout)

User dashboard to view/manage bookings

📄 Primary Page Descriptions
Page Name	Description
Property Listing View	Displays a grid or list of available properties with basic info: photo, price per night, location, and rating. Users can apply filters or search based on location, date, and guest count.
Listing Detailed View	Shows detailed information about a selected property: full description, amenities, host profile, reviews, price breakdown, and a booking form.
Simple Checkout View	Provides a streamlined interface for booking confirmation. Displays pricing summary, calendar selection, guest details, and payment input. Confirms successful booking after submission.

💡 Importance of a User-Friendly Design
A user-friendly design is crucial in a booking system because:

It reduces confusion and hesitation, increasing conversions

It improves trust and user satisfaction

It allows users to make informed decisions with fewer clicks

It enhances accessibility for all device types and user needs

It encourages return usage and positive word-of-mouth


## 🎨 Figma Design Properties
📘 Color Styles
Primary Color: #FF5A5F (Airbnb red)

Secondary Color: #008489 (teal blue)

Background Color: #FFFFFF (white)

Text Primary: #484848 (dark gray)

Text Secondary: #767676 (medium gray)

Border/Line: #EBEBEB (light gray)

Accent: #FFB400 (amber/yellow for icons or highlights)

🔤 Typography
Font Family: Circular Std (or fallback: Arial, sans-serif)

Font Weights:

Light: 300

Regular: 400

Medium: 500

Bold: 700

Font Sizes:

Headings: 32px, 24px, 18px

Body Text: 16px

Captions / Labels: 14px, 12px

(Note: These values are based on common Airbnb-style UI kits. Adjust based on the actual Figma file provided.)

🧩 Why Identifying Design Properties Is Important
Identifying the design properties of a mockup in Figma is critical because:

🎯 It ensures consistency across the UI

⚙️ It allows developers to translate visual design into code precisely

📏 It enables scalable and responsive layout decisions

🤝 It improves collaboration between designers and developers

⏱️ It reduces iteration cycles by minimizing visual guesswork


## 👥 Project Roles and Responsibilities
This project adopts a collaborative structure based on agile principles. Each role is defined with specific responsibilities to ensure smooth execution and delivery of the AirBnB Clone.

# Role	Key Responsibilities
Project Manager	- Oversees project timelines and deliverables
- Coordinates between team members
- Ensures that the project remains within scope and budget
Frontend Developers	- Build responsive user interfaces
- Translate Figma designs into code using HTML, CSS, JavaScript, and frameworks like React
- Handle client-side logic and API integration
Backend Developers	- Design and implement RESTful APIs
- Manage server-side logic, authentication, and database integration (e.g., Flask, Express(Nodejs), MySQL)
- Ensure data security and integrity
Designers (UI/UX)	- Create user-friendly wireframes and mockups in Figma
- Define design systems, color palettes, and typography
- Collaborate with frontend team to ensure design consistency
QA/Testers	- Write and run test cases for all app components
- Identify bugs and track issues
- Perform regression, unit, and integration testing
DevOps Engineers	- Set up deployment pipelines and manage cloud infrastructure
- Monitor system performance and handle CI/CD
- Ensure high system availability and backup processes
Product Owner	- Defines project vision and business goals
- Prioritizes features in the product backlog
- Acts as a liaison between stakeholders and the development team
Scrum Master	- Facilitates agile ceremonies (daily stand-ups, sprint reviews, retrospectives)
- Removes blockers and ensures team productivity
- Coaches team on agile practices

## 🧩 UI Component Patterns
This section outlines the planned reusable UI components that will form the foundation of the AirBnB Clone interface. These components will ensure consistency, scalability, and maintainability across the application.

🔧 Planned Components
Component	Description
Navbar	- A responsive top navigation bar that includes branding, search input, login/signup buttons, and user avatar when logged in. It remains sticky across pages and adapts for mobile views.
Property Card	- A reusable card component for listing properties. It includes a thumbnail image, price per night, rating, location, and a short description. Designed for use in grid or list views.
Footer	- A consistent footer for all pages containing navigation links, terms and policies, social icons, and contact details. It maintains layout integrity on all screen sizes.
Search Filter Bar	- A horizontal filter bar allowing users to specify location, dates, guests, and price range. This component interacts with the property listing dynamically.
Booking Summary Panel	- A side panel (usually on the listing detail page) summarizing price, dates selected, and a "Book Now" button. Validates inputs before checkout.
Modal Component	- Reusable modal (popup) component used for login, registration, booking confirmation, or alerts.
Button Variants	- Standardized primary, secondary, and icon buttons used throughout the application for interactions.

These components will be styled using a shared design system derived from the Figma mockups, ensuring brand consistency and responsiveness.



## Author
Andrew Laryea
