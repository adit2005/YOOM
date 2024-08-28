# Yoom - A Zoom Clone Built with Next.js and TypeScript

**Yoom** is a video conferencing application inspired by Zoom, built using the latest web technologies to provide a secure platform for creating, managing, and joining meetings. It includes a range of advanced features for a seamless online communication experience.

## Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Quick Start](#-quick-start)
- [Code Snippets](#-code-snippets)
- [Additional Resources](#-additional-resources)
- [Contributing](#-contributing)

## 🚀 Features

- **Authentication**: Secure user login using Clerk with options for social sign-on and traditional email/password methods.
- **New Meeting**: Start new meetings with configurable camera and microphone settings.
- **Meeting Controls**: Control meeting features such as recording, screen sharing, muting/unmuting, and managing participants.
- **Exit Meeting**: Allow participants to leave or end the meeting for all attendees.
- **Schedule Future Meetings**: Schedule future meetings with date and time input.
- **Past Meetings List**: View details and recordings of past meetings.
- **Personal Room**: A unique personal room link for instant meetings.
- **Join Meetings via Link**: Simple, secure link-based meeting joining.
- **Secure Real-time Functionality**: Real-time interactions with secure communication.
- **Responsive Design**: Adapts seamlessly to different devices and screen sizes.

## ⚙️ Tech Stack

- **Next.js** - React framework for building fast and SEO-friendly web applications.
- **TypeScript** - Type-safe JavaScript with static typing.
- **Clerk** - Authentication and user management.
- **getstream** - Real-time chat and activity feeds.
- **shadcn** - Component library.
- **Tailwind CSS** - Utility-first CSS framework for rapid styling.

## 🤸 Quick Start

### Prerequisites

Ensure you have the following installed:

- **Git**
- **Node.js**
- **npm** (Node Package Manager)

### Installation Steps

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/adit2005/yoom.git
    cd yoom
    ```

2. **Install Dependencies:**

    ```bash
    npm install
    ```

3. **Set Up Environment Variables:**

    Create a `.env` file in the root of your project with the following content:

    ```bash
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
    CLERK_SECRET_KEY=<your_clerk_secret_key>

    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

    NEXT_PUBLIC_STREAM_API_KEY=<your_stream_api_key>
    STREAM_SECRET_KEY=<your_stream_secret_key>
    ```

    Replace the placeholder values with your actual credentials from [Clerk](https://clerk.dev/) and [getstream](https://getstream.io/).

4. **Run the Project:**

    Start the development server:

    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## 🕸️ Code Snippets

- **Global Styles**: Found in `app/globals.css`.
- **Tailwind Configuration**: Configured in `tailwind.config.ts`.
- **Meeting Component**: Implemented in `components/MeetingCard.tsx`.

