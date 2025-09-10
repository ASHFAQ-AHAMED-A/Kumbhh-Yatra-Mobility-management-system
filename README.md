# Kumbh Yatra

A comprehensive digital pilgrimage management system for Mahakumbh Ujjain, featuring QR-based pass generation, crowd management, and real-time facility tracking.

## Features

- **QR Pass Generation**: Automated pass creation with heuristic gate allocation
- **Interactive Maps**: Real-time crowd density and facility tracking
- **Admin Dashboard**: Comprehensive management tools for events, drones, and facilities
- **Location Services**: GPS-based navigation and location tracking
- **Crowd Management**: Dynamic load balancing and capacity management

## Tech Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS with custom theme
- **Maps**: MapLibre GL JS with MapTiler
- **UI Components**: Radix UI primitives
- **State Management**: React hooks and localStorage
- **Testing**: Vitest with React Testing Library
- **Build Tool**: Vite

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd kumbh-yatra
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:8080`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm test` - Run tests
- `npm run test:ui` - Run tests with UI
- `npm run test:coverage` - Run tests with coverage

## Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Page components
├── hooks/              # Custom React hooks
├── utils/              # Utility functions
├── data/               # Mock data and constants
├── layouts/            # Layout components
└── test/               # Test utilities
```

## Key Features

### QR Pass System
- Automatic gate allocation using multi-factor heuristic algorithm
- Real-time capacity management
- Location-based optimization

### Interactive Maps
- Live crowd density visualization
- Facility status tracking
- Drone surveillance integration

### Admin Dashboard
- Event management
- Drone fleet control
- Real-time analytics

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License

This project is licensed under the MIT License.