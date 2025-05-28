# MeetingManager
MeetingManager is a modern React-based web application designed to help users create, manage, and comment on meetings. It features user authentication, role-based access, localization, responsive UI, and customizable themes.


## Features
**Authentication & Authorization**
  Register, login, logout, and role-based access (admin/user).

**Profile Management**
  Update name, email, and upload avatar image.

**Meetings Dashboard**
  View all meetings with author name and time, leave comments.

**User Meetings**
  Create and delete your own meetings.

**Language Support**
  Switch between English and Russian (EN/RU) using i18n.
  
**Theme Support**
  Toggle between Light and Dark modes.


## Technologies Used
* React (Create React App)
* React Router DOM
* Context API
* React Hooks (useState, useEffect, useContext)
* i18next for localization
* Toastify for notifications
* CSS (custom themes and responsive design)


## Folder Structure

```
/src
  /components     // Reusable components like Navbar, CommentBox
  /contexts       // Auth, Theme, Language providers
  /pages          // Route pages: Login, Profile, Meetings, Admin
  /routes         // ProtectedRoute, AdminRoute
  /styles         // Global and modular CSS
  App.jsx         // Main app layout and routes
  index.js        // Root file
```

## Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/your-username/meetingmanager.git
cd meetingmanager
```

2. **Install dependencies**

```bash
npm install
```

3. **Start the development server**

```bash
npm start
```