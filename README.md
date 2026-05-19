# Monochrome Transit Hub

A sleek, monochrome-themed web application for booking airline and railway tickets. Built with modern web technologies for a seamless reservation experience.

## 🚀 Features

### Core Functionality
- **Dual Transport Modes**: Search and book both flights and trains
- **Advanced Search**: Filter by departure/arrival locations, dates, passenger count, and cabin class
- **Real-time Results**: Instant trip search with generated mock data
- **Interactive Seat Selection**: Visual seat map for choosing preferred seats
- **Booking Management**: View, track, and cancel reservations
- **Responsive Design**: Optimized for desktop and mobile devices

### User Experience
- **Monochrome Theme**: Elegant black-and-white design with subtle accents
- **Smooth Navigation**: Single-page application with smooth scrolling
- **Toast Notifications**: Real-time feedback for user actions
- **Form Validation**: Comprehensive input validation for bookings
- **Accessibility**: Screen reader friendly with proper ARIA labels

### Additional Sections
- **Destinations Showcase**: Curated list of popular Indian destinations with pricing
- **Live Departures Board**: Real-time flight and train departure information
- **Hero Section**: Engaging landing page with call-to-action
- **Footer**: Contact information and additional links

## 🛠️ Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS with custom design system
- **UI Components**: Shadcn/ui (built on Radix UI primitives)
- **State Management**: TanStack Query for server state
- **Routing**: React Router
- **Icons**: Lucide React
- **Testing**: Vitest
- **Linting**: ESLint

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd monochrome-transit-hub
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **Open your browser** and navigate to `http://localhost:8080`

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # Shadcn/ui components
│   ├── BookingFlow.tsx # Multi-step booking process
│   ├── BookingsList.tsx# Reservation management
│   ├── Destinations.tsx# Destination showcase
│   ├── Header.tsx      # Navigation header
│   ├── Hero.tsx        # Landing section
│   ├── ResultsList.tsx # Search results display
│   ├── Schedule.tsx    # Departures board
│   ├── SearchPanel.tsx # Trip search interface
│   └── SeatMap.tsx     # Interactive seat selection
├── data/
│   └── mockData.ts     # Mock trip and location data
├── hooks/              # Custom React hooks
├── lib/
│   ├── bookingStore.ts # Booking state management
│   └── utils.ts        # Utility functions
├── pages/              # Route components
│   ├── Index.tsx       # Main application page
│   └── NotFound.tsx    # 404 error page
└── App.tsx             # Root component with routing
```

## 🎨 Design System

- **Color Palette**: Monochrome with foreground/background variables
- **Typography**: Custom display font with monospace accents
- **Spacing**: Consistent padding and margins using Tailwind
- **Components**: Modular, reusable UI components
- **Themes**: Dark/light mode support through CSS variables

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run test` - Run tests once
- `npm run test:watch` - Run tests in watch mode

## 🌟 Key Components

### SearchPanel
Allows users to search for trips by:
- Transport type (Flight/Train)
- Origin and destination
- Travel date
- Number of passengers
- Cabin class

### BookingFlow
3-step booking process:
1. **Trip Selection**: Choose from search results
2. **Seat Selection**: Interactive seat map
3. **Passenger Details**: Name and email input
4. **Confirmation**: Booking summary and reference

### SeatMap
- Visual representation of available seats
- Different layouts for flights (6 columns) and trains (4 columns)
- Real-time availability updates
- Accessible seat selection

### BookingsList
- Display all user reservations
- Show trip details and status
- Cancel bookings functionality
- Persistent storage using localStorage

## 📊 Mock Data

The application uses mock data for:
- Airport and railway station codes
- Trip generation with realistic pricing
- Seat availability simulation
- Carrier information

## 🚀 Deployment

1. **Build the application**:
   ```bash
   npm run build
   ```

2. **Deploy the `dist` folder** to your hosting provider (Vercel, Netlify, etc.)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linting
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 📞 Contact

For questions or support, please open an issue on GitHub.
