# HubSpot & Google Integrated Signup Form

## Overview

This project is a custom signup form designed to be integrated into a HubSpot landing page while also leveraging Google Places API for city based user inputs. The form is styled for a seamless user experience and supports automatic city suggestions, IP tracking, and structured input validation.

## Features

- **HubSpot Form Integration:** Uses HubSpot's embed script to connect the form with a HubSpot landing page.
- **Google Places API Integration:** Autocomplete feature for city selection.
- **IP Address Retrieval:** Captures user's IP address for enhanced tracking.
- **Responsive Design:** Fully responsive and mobile-friendly.
- **Enhanced Form Styling:** Improved form aesthetics for better user experience.

## Technologies Used

- HTML
- CSS
- JavaScript
- HubSpot Forms API
- Google Places API

## How It Works

1. Users fill in the required fields: First Name, Last Name, Email, and Nearest City.
2. The city input field leverages Google Places API to suggest locations.
3. Upon submission, user data is sent to HubSpot for lead management.
4. IP addresses are captured via an API call to `ipify` to store the user’s location context.

## Deployment

- You can host this project on any static hosting service such as GitHub Pages, Netlify, or Vercel.
