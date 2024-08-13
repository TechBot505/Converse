# Converse: A modern Video Conferencing Website
🤖 Introduction
Converse is a cutting-edge video conferencing platform designed to replicate and enhance the features of popular tools like Zoom. Built with Next.js and TypeScript, Converse allows users to securely log in, create meetings, and utilize a range of functionalities such as recording, screen sharing, and participant management.
🔋 Features
👉 User Authentication
Secure user login via social sign-on or email/password.
Role-based access control to ensure appropriate permissions.
👉 New Meeting
Instant meeting creation with configurable camera and microphone settings.
👉 Meeting Controls
Full participant control over meeting features:
Recording: Start and stop recording of meetings.
Screen Sharing: Share your screen with other participants.
Emoji Reactions: Express yourself with real-time reactions.
Participant Management: Pin, mute, unmute, or block participants, and manage their video sharing permissions.
👉 Schedule Future Meetings
Schedule meetings in advance by setting the date and time.
Upcoming meetings are accessible via the 'Upcoming Meetings' page, where users can share the meeting link or start the meeting immediately.
👉 Past Meetings
Access a comprehensive list of previously held meetings, including details and metadata.
👉 View Recorded Meetings
Review or reference recorded meetings with easy access to past meeting recordings.
👉 Personal Room
Every user has a personal meeting room with a unique link for instant meetings.
👉 Join Meetings via Link
Effortlessly join meetings created by others using a provided link.
👉 Secure Real-time Functionality
All interactions within the platform are secure and occur in real-time, ensuring privacy and data integrity.
👉 Responsive Design
Converse is designed to provide an optimal user experience across devices, with a responsive layout that adapts seamlessly to different screen sizes.
🤸 Quick Start
Prerequisites
Git
Node.js
npm (Node Package Manager)
Cloning the Repository
bash
Copy code
git clone https://github.com/yourusername/converse.git
cd converse
Installation
Install the project dependencies:

bash
Copy code
npm install
Set Up Environment Variables
Create a .env file in the root directory and add the following content:

makefile
Copy code
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your-clerk-publishable-key>
CLERK_SECRET_KEY=<your-clerk-secret-key>

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=<your-stream-api-key>
STREAM_SECRET_KEY=<your-stream-secret-key>
Running the Project
bash
Copy code
npm run dev
Open http://localhost:3000 in your browser to start using Converse.
