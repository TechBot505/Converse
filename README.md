
# Converse - Modern Video Conferencing Application

## Project Overview
Converse is a modern and secure video conferencing platform designed to facilitate seamless communication and collaboration. Users can create accounts, log in, and host or join meetings with ease. Converse offers a range of features, including meeting scheduling, recording, screen sharing, and participant management. Whether for personal or professional use, Converse provides a smooth and efficient experience, ensuring that all interactions are secure and in real-time. The platform is optimized for high performance, delivering a responsive and reliable service across all devices.

## Key Features
![image](https://github.com/user-attachments/assets/0bf85081-0893-4ebd-a482-2e5053277ebd)

1. **User Authentication:**
   - Secure login via social sign-on or email/password.
   - Authentication is implemented using ClerkAPI, ensuring secure and validated user sessions.

   ![image](https://github.com/user-attachments/assets/b52e2bda-f0b1-443a-94fd-89dfecd48042)

2. **New Meeting:**
   - Instant meeting creation with configurable camera and microphone settings.
     
   ![image](https://github.com/user-attachments/assets/30f4852d-9ca3-4cb0-afca-5c25a2d5afde)

3. **Meeting Controls:**
   - Participants have full control over meeting features:
     1. **Recording:** Start and stop meeting recordings.
     2. **Screen Sharing:** Share your screen with other participants.
     3. **Emoji Reactions:** Express yourself with real-time reactions.
     4. **Participant Management:** Pin, mute, unmute, or block participants, and manage video sharing permissions.
        
    ![image](https://github.com/user-attachments/assets/473d0a1e-27cf-4fce-bb51-05f21d53f94a)

4. **Schedule Future Meetings:**
   - Schedule meetings in advance by setting the date and time.
   - Access upcoming meetings on the 'Upcoming Meetings' page to share links or start meetings.
     
   ![image](https://github.com/user-attachments/assets/1d9b92e4-80a1-41ca-bbfc-e812b3c6eece)

5. **Past Meetings:**
   - View a comprehensive list of previously held meetings, including details and metadata.
  

6. **View Recorded Meetings:**
   - Review or reference recorded meetings easily.
     
      ![image](https://github.com/user-attachments/assets/39c4fba1-5dfc-4502-b438-abc11e3ad346)

7. **Personal Room:**
   - Each user has a personal meeting room with a unique link for instant meetings.

8. **Join Meetings via Link:**
   - Easily join meetings using a provided link.

9. **Secure Real-time Functionality:**
   - Interactions are secure and occur in real-time, ensuring privacy and data integrity.

10. **Responsive Design:**
    - The platform adapts seamlessly to different screen sizes, providing an optimal user experience across devices.
   
## Tech Stacks
- **Frontend:** Next, TypeScript, Tailwind CSS, Shadcn
- **Authentication:** Clerk Auth
- **Real-time Communication:** Stream-API
- **State Management:** Context API
- **Deployment and Containarization:** Docker
## Local Setup

### Prerequisites
- Git
- Node.js
- npm (Node Package Manager)
- Docker (Deamon Installed)

### Cloning the Repository
```bash
git clone https://github.com/TechBot505/Converse.git
cd converse
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

To start the project using Docker, use the following command:

```bash
docker compose up
```

This will start the necessary containers and run the project.

### Live Changes

To enable live changes, use the following command:

```bash
docker compose watch
```

This command will monitor for changes and apply them automatically during development.

Alternatively, to start the project without using Docker, use the following command:

```bash
npm run start
```

Open `http://localhost:3000` in your browser to start using Converse.



## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the project's style and passes all tests before submitting.


