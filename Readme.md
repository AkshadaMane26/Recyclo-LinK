# ♻️ Recyclo-LinK -- Smart Waste Management System ♻️

## Introduction

WasteWise is a web-based platform designed to streamline waste management for societies by promoting sustainable waste disposal practices, optimizing waste collection schedules, and encouraging recycling through community engagement. The system integrates features like waste collection coordination, a marketplace for recyclable items, a reward system, and an intelligent notification system.

## Features

### 1. **User Features**

- Upload photos of waste (e.g., clothes, toys, unused materials) with descriptions, pricing, and contact information.
- Mark favorite products for easy access.
- Receive notifications for waste collection schedules and event waste coordination.
- Access guidelines and video tutorials on waste segregation and recycling.
- Utilize a chatbot assistant for queries.
- Multilingual support for a diverse user base.

### 2. **Admin Features**

- Set and manage waste collection schedules with email/SMS notifications.
- Approve or decline waste collection requests from collectors.
- Moderate user-uploaded products to ensure compliance with platform rules.

### 3. **Waste Collector Features**

- View nearby recyclable items listed by residents.
- Send collection requests to users.
- Get notified about upcoming collection schedules.

## Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT-based authentication
- **Notifications:** Email/SMS integration
- **AI Integration:** Chatbot for waste management guidance

## Sanpshots of UI

<body>
<details>
    <summary>click Here to view</summary>
    <ul>
        <li>
            <img src="react-app\Output\Home.png" alt="form" height="100">
        </li>
        <li>
            <img src="react-app\Output\Initiative.png" alt="form" height="100">
        </li>
        <li>
            <img src="react-app\Output\GuidelinesAndTutorial.png" alt="form" height="100">
        </li>
        <li>
            <img src="react-app\Output\WasteSection.png" alt="form" height="100">
        </li>
        <li>
            <img src="react-app\Output\Notification.png" alt="form" height="100">
        </li>
        <li>
            <img src="react-app\Output\Reward.png" alt="form" height="100">
        </li>
        <li>
            <img src="react-app\Output\Profile.png" alt="form" height="100">
        </li>
    </ul>

</details>

## Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/Harshada-Borse/Recyclo-LinK.git
   cd waste-management-wedsite
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   EMAIL_SERVICE=your_email_service_provider
   ```
4. Start the backend server:
   ```sh
   npm run server
   ```
5. Start the frontend application:
   ```sh
   npm start
   ```

<p><code>Thank you!🧑‍💻</code></p>

</body>
