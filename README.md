# 🎮 Game Paradise - PlayStation Store

A modern and responsive PlayStation game store web application.

## 🌐 Live Demo

**🔗 View Live Website:** [https://pooyansaeedinia.github.io/GAME-PARADISE/](https://pooyansaeedinia.github.io/GAME-PARADISE/)

**📱 Demo Features:**
- Fully responsive design
- Interactive product pages
- User authentication UI
- Product catalog browsing
- Modern navigation system

## 📋 Project Overview

Game Paradise is a frontend web application designed as an online marketplace for PlayStation games, consoles, and accessories. This project demonstrates modern web development practices with a clean, user-friendly interface.

## ✨ Features

- **E-commerce Platform**: Online store for PlayStation games and products
- **User Authentication**: Secure login and registration system
- **Product Catalog**: Organized game listings with detailed pages
- **Responsive Design**: Mobile-friendly interface
- **Modern UI/UX**: Clean and intuitive user experience
- **Product Details**: Comprehensive game information with galleries

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with custom fonts and animations
- **Font Awesome**: Icon library for UI elements
- **Montserrat Font**: Typography design
- **Responsive Design**: Flexbox-based layouts

## 📁 Project Structure
text
```
GAME-PARADISE/
├── index.html # Homepage with featured products
├── login.html # User login page
├── register.html # User registration page
├── the_last_of_us_2.html # Sample product detail page
├── assets/
│ ├── css/
│ │ ├── index.css # Homepage styles
│ │ ├── login.css # Authentication pages styles
│ │ └── product.css # Product page styles
│ ├── images/ # Product images and logos
│ ├── fonts/ # Montserrat font family
│ └── media/ # Media files
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Local server for development

### Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/pooyansaeedinia/GAME-PARADISE.git
```
2. **Navigate to the project directory:**
text
```
cd GAME-PARADISE
```
3. **Run with a local server:**
- Method 1: Using Python
text
```
python -m http.server 8000
```
- Method 2: Using PHP
text
```
php -S localhost:8000
```
- Method 3: Using Node.js (if http-server is installed)
text
```
npx http-server
```
- Method 4: Using VS Code Live Server
text
```
Install Live Server extension
Right-click on index.html
Select "Open with Live Server"
```
4. **Open your browser and visit:**
text
```
http://localhost:8000
```

## 🎨 Pages Description

### 🏠 Homepage (`index.html`)
- **Header Section**: Navigation menu, search bar, login/support links
- **Featured Posters**: Promotional game banners with hover effects
- **Newest Products**: Grid layout showcasing latest game releases
- **Product Cards**: Individual game displays with images and pricing
- **Footer**: Company logo, navigation links, social media, and description

### 🔐 Authentication Pages

#### Login Page (`login.html`)
- **Login Form**: Username and password fields
- **Form Validation**: Required field validation
- **Additional Links**: 
  - "Forgot Password?" option
  - "Create Account" redirect
- **Terms Notice**: Privacy and policy acceptance reminder

#### Registration Page (`register.html`)
- **Sign-up Form**: Username, password, and password confirmation
- **Password Verification**: Confirm password matching
- **Existing Account Link**: Redirect to login page
- **Terms Acceptance**: Rules and policy agreement notice

### 🎯 Product Page (`the_last_of_us_2.html`)

#### Product Overview
- **Game Poster**: Large display image (500x500px)
- **Product Details**:
  - Game title and developer information
  - Release date and genre
  - Stock availability status

#### Purchase Options
- **Edition Selection**: 
  - Standard Edition
  - Deluxe Edition  
  - Premium Edition
- **Add to Cart**: Interactive buttons for each edition

#### Media Section
- **Image Gallery**: 6-image grid showcasing gameplay
- **Video Trailer**: Embedded video player with controls
- **Gameplay GIFs**: Animated gameplay demonstrations

#### Content Sections
- **Description Fieldset**: Detailed game story and plot
- **Gameplay Fieldset**: Mechanics and features explanation
- **Comments Fieldset**: User review and rating system

#### User Interaction
- **Comment Form**: Name input and comment textarea
- **Submit Button**: Comment submission functionality
- **Existing Comments**: Display of user reviews with usernames

### 🧭 Navigation Structure
- **Header Navigation**: Home, News, Game List, Store, Ranking, Contact Us
- **Footer Navigation**: Same as header for consistency
- **Breadcrumb Links**: Easy navigation between related pages
- **Call-to-Action Buttons**: Prominent login/support links

### 📱 Responsive Features
- **Flexible Layouts**: Adapts to different screen sizes
- **Hover Effects**: Interactive element animations
- **Image Optimization**: Proper sizing and border radius
- **Typography Hierarchy**: Clear heading and text structure

## License

This project is licensed under the MIT License.
