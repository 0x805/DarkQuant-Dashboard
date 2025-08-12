# DarkQuant Dashboard

A modern, responsive DeFi portfolio analytics dashboard that connects to Google Sheets for real-time data visualization.

## 🚀 Features

- **Real-time Data Integration**: Connects to Google Sheets via gviz API
- **Modern DeFi Design**: Glass morphism UI with dark theme
- **Interactive Charts**: Custom SVG line charts for portfolio analytics
- **KPI Dashboard**: Real-time metrics including Deposits, TVL, PNL, and Growth
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Search & Filter**: Real-time data filtering capabilities
- **Auto-refresh**: Live data updates with manual refresh option

## 📊 Dashboard Components

### Key Performance Indicators (KPIs)
- **Deposits**: Total portfolio deposits
- **TVL**: Total Value Locked
- **PNL**: Profit and Loss
- **Growth**: Portfolio growth percentage

### Data Visualization
- **Portfolio Table**: Complete data view with all accounts
- **Fund Share Chart**: Visual representation of fund distribution
- **Gains Chart**: Capital gains performance over time

## 🛠️ Technical Stack

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Data Source**: Google Sheets API (gviz JSON endpoint)
- **Charts**: Custom SVG implementation
- **Styling**: CSS Grid, Flexbox, Glass morphism effects
- **Fonts**: Inter (Google Fonts)

## 📁 File Structure

```
DarkQuant/
├── darkquant_dashboard.html    # Main dashboard file
└── README.md                   # Project documentation
```

## 🔧 Setup Instructions

### 1. Google Sheets Configuration
1. Make your Google Sheet publicly accessible
2. Update the `SHEET_ID` and `GID` variables in the HTML file:
   ```javascript
   const SHEET_ID = 'your-sheet-id-here';
   const GID = 'your-gid-here';
   ```

### 2. Local Development
1. Clone this repository
2. Open `darkquant_dashboard.html` in a web browser
3. The dashboard will automatically load data from your Google Sheet

### 3. Hosting Options
- **GitHub Pages**: Enable in repository settings
- **Netlify**: Drag and drop the HTML file
- **Vercel**: Connect your GitHub repository
- **Any web server**: Upload the HTML file

## 🌐 Live Demo

The dashboard includes fallback sample data if the Google Sheets connection fails, ensuring it always displays content.

## 📱 Responsive Design

The dashboard is fully responsive and optimized for:
- Desktop (1920px+)
- Tablet (768px - 1024px)
- Mobile (320px - 768px)

## 🔒 Security Notes

- Uses CORS proxies for Google Sheets API access
- No sensitive data is stored locally
- All data processing happens client-side

## 📈 Future Enhancements

- [ ] Real-time WebSocket updates
- [ ] Additional chart types (pie, bar, area)
- [ ] Export functionality (PDF, CSV)
- [ ] User authentication
- [ ] Multiple portfolio support

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ for the DeFi community**
