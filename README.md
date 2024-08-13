
# Converse - Modern Video Conferencing Application

## 📋 Table of Contents
- [Introduction](#introduction)

- [Features](#features)
- [Quick Start](#quick-start)
-  [Tech Stack](#tech-stack)
- [Assets & Code](#assets--code)


## Introduction
Converse is a modern video conferencing platform designed to replicate and enhance the features of popular tools like Zoom. Built with Next.js and TypeScript, Converse allows users to securely log in, create meetings, and utilize a range of functionalities such as recording, screen sharing, and participant management.



## Features
- **User Authentication:** Secure login via social sign-on or email/password. Role-based access control ensures appropriate permissions.
- **New Meeting:** Instant meeting creation with configurable camera and microphone settings.
- **Meeting Controls:** Participants have full control over meeting features:
  - Recording: Start and stop meeting recordings.
  - Screen Sharing: Share your screen with other participants.
  - Emoji Reactions: Express yourself with real-time reactions.
  - Participant Management: Pin, mute, unmute, or block participants, and manage video sharing permissions.
- **Schedule Future Meetings:** Schedule meetings in advance by setting the date and time. Access upcoming meetings on the 'Upcoming Meetings' page to share links or start meetings.
- **Past Meetings:** View a comprehensive list of previously held meetings, including details and metadata.
- **View Recorded Meetings:** Review or reference recorded meetings easily.
- **Personal Room:** Each user has a personal meeting room with a unique link for instant meetings.
- **Join Meetings via Link:** Easily join meetings using a provided link.
- **Secure Real-time Functionality:** Interactions are secure and occur in real-time, ensuring privacy and data integrity.
- **Responsive Design:** The platform adapts seamlessly to different screen sizes, providing an optimal user experience across devices.

## Quick Start

### Prerequisites
- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository
```bash
git clone https://github.com/yourusername/converse.git
cd converse
```

### Installation
Install the project dependencies:
```bash
npm install
```

### Set Up Environment Variables
Create a `.env` file in the root directory and add the following content:
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your-clerk-publishable-key>
CLERK_SECRET_KEY=<your-clerk-secret-key>

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=<your-stream-api-key>
STREAM_SECRET_KEY=<your-stream-secret-key>
```

### Running the Project
```bash
npm run dev
```
Open `http://localhost:3000` in your browser to start using Converse.

## Tech Stack
- **Frontend:** Next.js, TypeScript, Tailwind CSS, shadcn
- **Authentication:** Clerk
- **Real-time Communication:** getstream
- **State Management:** Context API

## Assets & Code
This project includes both frontend and backend components. The frontend is built with Next.js and Tailwind CSS, while the backend uses Node.js for handling API requests and real-time communication.


