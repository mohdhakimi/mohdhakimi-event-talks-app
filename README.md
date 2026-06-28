# TechTalks 2026 - 1-Day Event Website

A professional, single-page website for a 1-day technical event. This application features a chronological schedule of talks, a Node.js backend, and a real-time category search.

## 🚀 Features

- **Dynamic Schedule:** A full-day timeline (10:00 AM – 5:40 PM) including 6 technical talks, transition breaks, and a lunch hour.
- **Instant Search:** Filter talks by category (e.g., "Cloud", "AI", "JS") as you type.
- **Responsive Design:** A "Corporate Blue" themed UI that looks great on desktops, tablets, and mobile devices.
- **Hybrid Serving:** Can be served as a standalone static file or via the included Node.js server.

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Vanilla), JavaScript (ES6+)
- **Backend:** Node.js, Express
- **Preview:** Standalone `index.html`

## 📋 Schedule Overview

| Event | Time |
| :--- | :--- |
| **Talk 1: Architecting Scalable Microservices** | 10:00 AM - 11:00 AM |
| **Talk 2: Modern Frontend with Web Components** | 11:10 AM - 12:10 PM |
| **Talk 3: AI in Production: Best Practices** | 12:20 PM - 01:20 PM |
| **Lunch Break** | 01:20 PM - 02:20 PM |
| **Talk 4: Cybersecurity Trends for 2026** | 02:20 PM - 03:20 PM |
| **Talk 5: Mastering TypeScript for Enterprise** | 03:30 PM - 04:30 PM |
| **Talk 6: The Future of Edge Computing** | 04:40 PM - 05:40 PM |

## 💻 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (for the backend server)
- [Python 3](https://www.python.org/) (optional, for quick static preview)

### Option 1: Run with Node.js (Recommended)

1. Clone the repository:
   ```bash
   git clone https://github.com/mohdhakimi/mohdhakimi-event-talks-app.git
   cd mohdhakimi-event-talks-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm start
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 2: Quick Static Preview

If you just want to see the frontend without installing Node dependencies, you can serve the `index.html` file using Python:

```bash
python3 -m http.server 8000
```
Then visit [http://localhost:8000](http://localhost:8000).

## 📄 License

This project is open-source and available under the MIT License.
