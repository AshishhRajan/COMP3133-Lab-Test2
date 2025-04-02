SpaceX Missions Explorer

Author

Ashish Rajan SherryStudent ID: 101423478

Overview

This is an Angular application that displays SpaceX mission data. It fetches mission details from the SpaceX REST API and provides filtering options based on launch year, launch success, and landing success.

Features

Display a list of SpaceX missions

Filter missions by:

Launch year

Successful or failed launches

Successful or failed landings

View detailed information about each mission

Responsive design using Angular Material

Technologies Used

Angular (Frontend framework)

TypeScript (Programming language)

Angular Material (UI components)

SpaceX API (Data source)

Flexbox & Grid (CSS layout)

Setup & Installation

Prerequisites

Ensure you have the following installed:

Node.js (>= 14.x)

Angular CLI (>= 13.x)

Steps to Run the Application

Clone this repository:

git clone https://github.com/AshishhRajan/spacex-missions.git
cd spacex-missions

Install dependencies:

npm install

Run the application:

ng serve

Open your browser and visit http://localhost:4200

API Integration

This project fetches SpaceX launch data from the SpaceX REST API. The API endpoint used is:

https://api.spacexdata.com/v3/launches

Project Structure

spacex-missions/
├── src/
│   ├── app/
│   │   ├── components/
│   │   ├── services/
│   │   ├── models/
│   ├── assets/
│   ├── environments/
├── angular.json
├── package.json
├── README.md

Deployment

To build the application for production:

ng build --prod

Then, deploy the generated dist/ folder to any static hosting provider like Firebase, Vercel, or Netlify.

License

This project is for educational purposes only.

Contact

For any queries, reach out to Ashish Rajan Sherry at [your-email@example.com].

