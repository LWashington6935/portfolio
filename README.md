# Portfolio of Lucas Washington

Welcome to my personal portfolio showcasing my **Equity Vesting Dashboard** project.

---

## 📌 Live Demo
Access the live application here:

> https://LWashington6935.github.io/portfolio/dashboard/

## 📂 Repository Structure
```
portfolio/
├── index.html             # Portfolio homepage
├── styles.css             # Homepage styles
├── script.js              # Homepage scripts (if any)
├── README.md              # This file
└── dashboard/             # Deployed React/Vite dashboard
    ├── index.html         # Dashboard entry point
    └── assets/            # Built assets (JS, CSS, images)
```

## 🚀 Equity Vesting Dashboard
An interactive React application that allows employees to:

- Toggle between **ALL**, **US**, and **UK** stock-option grants
- View a live **grants table** with current prices and calculated market values
- See upcoming and past vesting dates on a **FullCalendar** view
- Click dates to drill into **event details**
- Add and persist **custom notes** via `localStorage`

### Key Features

| Feature                      | Description                                                    |
|------------------------------|----------------------------------------------------------------|
| Region Toggle                | Filter grants by region using React state                     |
| Data Fetching                | Live API calls for grants, FX rates, and stock prices         |
| Calendar Integration         | FullCalendar DayGrid plugin with `dateClick` handlers         |
| Persistent Notes             | Save personal notes locally between sessions                  |
| Responsive Design            | Styled with Tailwind CSS utility classes                      |

### Tech Stack

- **Frontend:** React, Vite
- **Calendar:** @fullcalendar/react + dayGridPlugin
- **Charts:** Chart.js via react-chartjs-2
- **Styling:** Tailwind CSS, custom CSS
- **API:** Node.js + Express (deployed on Render)

## 🔧 Installation & Local Development

1. **Clone the dashboard repo** and install dependencies:
   ```bash
   git clone https://github.com/LWashington6935/vesting-backend.git
   cd vesting-backend
   npm install
   npm start    # Runs backend server on http://localhost:4000
   ```

2. **Clone the portfolio repo** and install dependencies:
   ```bash
   git clone https://github.com/LWashington6935/portfolio.git
   cd portfolio/dashboard
   npm install
   npm run dev  # Runs dashboard on http://localhost:5173
   ```

3. **View in browser:**
   - Portfolio homepage: http://localhost:5500 (or via Live Server)
   - Dashboard: http://localhost:5173/dashboard/

## 🌐 Deployment

- **Frontend:** Served via GitHub Pages from `main` branch, root folder
- **Backend:** Deployed on Render at https://vesting-backend-wswd.onrender.com

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
# e.g.-portfolio
