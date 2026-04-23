# MasaMaster (Light Edition)

Professional Masaniello money management system for structured betting and investment strategies. Built with React, TypeScript, and Tailwind CSS.

![MasaMaster Dashboard](https://images.unsplash.com/photo-1611974714851-eb6051616803?q=80&w=2070&auto=format&fit=crop)

## Features

- **Masaniello Algorithm**: Advanced probabilistic bankroll management.
- **Light Theme**: Clean, modern, and high-contrast UI using Tailwind CSS.
- **Mobile First**: Fully responsive design with adaptive views for desktop and mobile.
- **Real-time Analytics**: Live calculation of yields, stakes, and progression status.
- **Interactive Charts**: Visualize your capital flow with Recharts.
- **History Tracking**: Comprehensive activity log with undo capabilities.
- **Browser Persistence**: Automatic local storage saving of your current session.

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/masamaster-light.git
   cd masamaster-light
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## How to Use

1. **Initial Setup**: Enter your initial capital, event odds (fixed), total events, and expected wins.
2. **Progression**: The app will calculate your first stake.
3. **Record Results**: Use the "WIN" or "LOSS" buttons after each event.
4. **Follow the Algorithm**: The system recalculates the next stake automatically to ensure you reach your goal if your expected win count is met.
5. **Reset**: Use the Reset button in the navigation bar to start a new session.

## Technologies Used

- **Framework**: [React 19](https://react.dev/)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Animations**: [Motion](https://motion.dev/)
- **Charts**: [Recharts](https://recharts.org/)
- **Build Tool**: [Vite 6](https://vitejs.dev/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
