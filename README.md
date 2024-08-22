# SIH1630-CursiveCoders

# Mentoring Platform Prototype

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Implementation Details](#implementation-details)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

Mentoring during the career/education phase is crucial for the success of a candidate. This platform connects candidates with mentors who can guide them in their career and skill development journey. The platform allows candidates to book mentoring sessions based on the mentor's availability, conduct virtual meetings with an embedded video call feature, and chat securely during sessions.

## Features

- **User Registration & Login:** Secure registration and login system for both mentors and mentees.
- **Profile Creation:** Mentors and mentees can create and manage their profiles.
- **Automated Calendar Booking:** Candidates can book mentoring sessions based on mentor availability, with automatic scheduling.
- **Embedded Video Call:** Virtual meetings facilitated through an embedded video call feature with chat functionality.
- **Session Feedback:** Users can provide feedback after each session to improve the platform.

## Technologies Used

- **Frontend:** React.js for building a responsive user interface.
- **Backend:** Django (Python) for managing the backend logic and API development.
- **Database:** PostgreSQL for storing user data, appointments, and feedback.
- **Video Call Integration:** WebRTC for real-time video calls, Twilio API for video and chat functionalities.
- **Deployment:** Vercel for cloud hosting and deployment.

## Getting Started

### Prerequisites

Ensure you have the following installed on your development environment:

- [Node.js](https://nodejs.org/)
- [Python 3.x](https://www.python.org/downloads/)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/mentoring-platform.git
   cd mentoring-platform

## Folder Structure

mentoring-platform/
├── frontend/           # React.js frontend code
├── backend/            # Django backend code
├── docs/               # Documentation and resources
├── .gitignore          # Git ignore file
├── README.md           # Project documentation
└── LICENSE             # License information


## We welcome contributions from the team! Here's how you can help:

1. Fork the repository
2. Create a branch: git checkout -b feature/your-feature
3. Commit your changes: git commit -m 'Add your feature'
4. Push to the branch: git push origin feature/your-feature
5. Submit a pull request


## mplementation Details
1. Frontend
----------------------------------------------------------------------------------------------------------------------
React Components: Each major feature is implemented as a React component, with routing handled by react-router-dom.
State Management: Utilize Context API or Redux for state management.

2. Backend
----------------------------------------------------------------------------------------------------------------------
Django Models: Define models for User, Profile, Appointment, and Feedback.
API Endpoints: RESTful APIs for user authentication, profile management, booking, and feedback.
Integration: Calendar integration using Google Calendar API or Calendly for appointment booking.

3. Video Call
-----------------------------------------------------------------------------------------------------------------------
WebRTC: Used for peer-to-peer video communication.
Twilio: Embedded video calls with real-time chat.
