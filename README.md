# KatoMine

KatoMine is a web-based platform that allows users to mine **Kato tokens**, invite friends using referral links, and manage their wallet balance. Built with a modern and responsive design, it ensures a seamless experience across devices. The platform integrates Firebase for real-time data management and EmailJS for contact form functionality, providing an intuitive and user-friendly interface.

## Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Firebase Configuration](#firebase-configuration)
- [EmailJS Configuration](#emailjs-configuration)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Mining System**: Start an 8-hour mining session to earn Kato tokens (`claim.html`).
- **Referral System**: Invite friends using a unique referral ID to earn bonus tokens (up to 10 referrals per user) (`invite.html`).
- **Wallet Management**: View and manage your Kato token balance in real-time (`wallet.html`).
- **Responsive Design**: Optimized for mobile and desktop with dynamic font sizes and layouts using CSS `clamp`.
- **Firebase Integration**: Real-time storage and retrieval of user data (balances, referrals, mining status, usernames).
- **User Verification**: Verify accounts with usernames and recover accounts using an 8-digit Recovery Code (`index.html`).
- **Referral Code Copy**: Copy referral links with a single click for easy sharing (`index.html`).
- **Extra Rewards**: Complete simple tasks to earn additional Kato tokens (`extrareward.html`).
- **Roadmap**: View the platform’s future plans and updates (`roadmap.html`).
- **Contact Form**: Send messages to the support team via an EmailJS-powered contact form (`contact-us.html`).
- **Informational Pages**: Access detailed Privacy Policy, Terms of Service, and About Us pages (`privacy-policy.html`, `terms-of-service.html`, `about-us.html`).
- **Navigation Bar**: Seamless navigation across Home, Claim, Invite, Wallet, and footer links (Privacy Policy, Terms of Service, About Us, Contact Us).
- **Multilingual Support**: Includes Bangla text (e.g., "যোগাযোগ করুন" in `terms-of-service.html`).

## Project Structure
## Technologies Used
- **HTML5**: Structure of the web pages.
- **CSS3**: Styling with responsive design using `clamp` for font sizes and layouts.
- **JavaScript (ES Modules)**: Client-side logic for mining, referrals, wallet, and form submissions.
- **Firebase (v10.14.1)**: Real-time database for user data (balances, referrals, mining status).
- **EmailJS (v3)**: Contact form functionality for sending messages to support.
- **Font Awesome (v6.5.1)**: Icons for navigation and UI elements.
- **GitHub Pages**: Hosting the static website at `https://katomineconnect.github.io/KatoMine.com/`.

## Setup Instructions
To set up and run the project locally or deploy it, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/katomineconnect/KatoMine.com.git
   cd KatoMine.com