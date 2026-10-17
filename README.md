# Employee Management App

A full-stack mobile application for managing employees and tracking attendance, built with **React Native (Expo)**, **Node.js (Express)**, and **MongoDB**.

## Features

- **Employee Directory**: View all registered employees with real-time search filtering.
- **Add Employee**: Register new employee details (Name, ID, Designation, Phone, Salary, Address, Joining Date, etc.).
- **Attendance Management**: Mark daily employee attendance (Present, Absent, Half Day, Holiday) with ease.
- **Attendance Summary & Reports**: Visualize attendance history, status counts, and generate summaries.

## Project Structure

```text
├── api/                  # Backend Node.js / Express API
│   ├── index.js          # Express server & API endpoints
│   ├── models/           # Mongoose schemas (Employee, Attendance)
│   └── package.json      # API dependencies
├── app/                  # Expo Router screens & layouts
│   ├── (home)/           # Home screens (employees, attendance, summary, etc.)
│   └── _layout.js        # Root layout configuration
├── assets/               # App icons and splash assets
├── components/           # Reusable UI components
├── app.json              # Expo app configuration
└── package.json          # Frontend dependencies
```

## Getting Started

### Prerequisites

- Node.js (v18+)
- npm or yarn
- Expo Go app on your physical mobile device (or iOS Simulator / Android Emulator)
- MongoDB instance (Atlas or local)

### 1. Backend Setup

```bash
cd api
npm install
node index.js
```

The API server will run on `http://localhost:8000`.

### 2. Frontend Setup

```bash
# In the project root directory
npm install
npx expo start
```

Scan the QR code with Expo Go (Android) or the Camera app (iOS) to launch the app.
