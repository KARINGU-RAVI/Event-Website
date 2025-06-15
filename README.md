# 🎟️ Event Discovery Platform

A modern, responsive web application that enables users to discover and explore upcoming and recommended events with ease.

## 📌 Project Overview

This Event Discovery Platform helps users stay updated with live and trending events. The app integrates secure authentication, dynamic API-driven content, and a sleek UI/UX built on modern frontend tools. Optimized for both desktop and mobile experiences.

---

## 🚀 Features

- 🔐 **User Authentication**: Signup and login with validation and session management.
- 📱 **Responsive Design**: Works seamlessly on desktops, tablets, and mobile devices.
- 🦸 **Hero Section**: Prominent banner showcasing key events and promotions.
- 🌟 **Recommended Shows**: A horizontally scrollable section of 8 curated events.
- 📅 **Upcoming Events**: Vertical scroll with lazy loading for efficient data fetching.
- 🔗 **API Integration**: Fetches data from external REST APIs.
- 🧠 **Modern UI/UX**: Crafted using `shadcn/ui` and styled with Tailwind CSS.
- ⚡ **Performance Optimized**: Vite bundling, lazy loading, and efficient rendering.

---

## 🛠️ Tech Stack

| Tech           | Purpose                                   |
|----------------|-------------------------------------------|
| **Vite**       | Lightning-fast frontend tooling           |
| **TypeScript** | Type-safe, scalable JavaScript alternative|
| **React**      | Declarative UI library                    |
| **shadcn/ui**  | Accessible, styled UI components          |
| **Tailwind CSS**| Utility-first CSS framework              |

---

## 🎨 Design Specifications

- **Font Family**: Inter
- **Heading Color**: `#1E2022`
- **Subtitle Color**: `#989090`
- **Background Color**: `#ffffff`
- **Logo Color**: `#CF2D2D`
- **Border/Stroke Color**: `#B0BABF`
- **Banner Image**: Included in `public/`

---

## 📡 API Endpoints

- **Recommended Shows**  
  `https://gg-backend-assignment.azurewebsites.net/api/Events?code=FOX643kbHEAkyPbdd8nwNLkekHcL4z0hzWBGCd64Ur7mAzFuRCHeyQ==&type=reco`

- **Upcoming Events (Paginated)**  
  `https://gg-backend-assignment.azurewebsites.net/api/Events?code=FOX643kbHEAkyPbdd8nwNLkekHcL4z0hzWBGCd64Ur7mAzFuRCHeyQ==&page=1&type=upcoming`

---

## ⚙️ Getting Started

### 📋 Prerequisites

Ensure you have the following installed:

- Node.js (LTS recommended)
- npm or Yarn

### ⬇️ Installation

```bash
git clone https://github.com/KARINGU-RAVI/Event-Website.git
cd Event-Website
npm install     # or yarn install
