# Simple-Portfolio-Tracker-
A stock portfolio management web application is developed using React, Java Spring Boot, and MySQL. It features a dashboard, adding/editing options, and a table. The app is deployed on platforms like Heroku and Netlify for a seamless user experience.


# Stock Portfolio Dashboard

A modern, responsive web application for managing and tracking stock investments. Built with React, TypeScript, and Tailwind CSS.

![Stock Portfolio Dashboard](https://images.unsplash.com/photo-1611974789855-9c2a0a7236a3?auto=format&fit=crop&q=80&w=1200)

## Features

- 📊 Real-time portfolio metrics
  - Total investment value
  - Current portfolio value
  - Profit/Loss tracking
  - Return percentage

- 💼 Stock Management
  - Add new stocks to portfolio
  - Edit existing stock details
  - Remove stocks from portfolio
  - View all holdings in a sortable table

- 📱 Responsive Design
  - Works seamlessly on desktop and mobile
  - Modern, clean user interface
  - Interactive components

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Lucide React (for icons)
- Vite (build tool)

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## Project Structure

```
src/
├── components/           # React components
│   ├── DashboardMetrics.tsx
│   ├── StockForm.tsx
│   └── StockTable.tsx
├── types/               # TypeScript interfaces
│   └── index.ts
├── App.tsx             # Main application component
└── main.tsx           # Application entry point
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Icons provided by [Lucide](https://lucide.dev/)
- Styling powered by [Tailwind CSS](https://tailwindcss.com/)
