# Sculpture Gallery App

A modern, interactive React application for exploring famous sculptures from around the world. Browse through a curated collection of iconic artworks with detailed information about each piece.

## Overview

This application showcases a collection of 12 famous sculptures, featuring works from renowned artists such as Marta Colvin Andrade, Eduardo Catalano, Niki de Saint Phalle, and Barbara Hepworth. Users can navigate through the collection, view high-quality images, and learn about each sculpture's history and significance.

## Features

- **Interactive Navigation**: Browse through sculptures one by one with a "Next" button
- **Toggle Details**: Show or hide detailed descriptions for each sculpture
- **Responsive Design**: Clean and modern UI that adapts to different screen sizes
- **Rich Content**: High-quality images and comprehensive information about each artwork
- **Event Handling**: Demonstrates React event propagation and state management

## Tech Stack

- **React** (v19.2.0) - UI library for building the user interface
- **Vite** (v7.2.2) - Fast build tool and development server
- **ESLint** - Code quality and style enforcement
- **CSS** - Custom styling for a polished look

## Project Structure

```
sculpture-app/
├── src/
│   ├── components/
│   │   └── SculpturesList.jsx    # Main sculpture display component
│   ├── App.jsx                   # Root application component
│   ├── App.css                   # Application styles
│   ├── main.jsx                  # Application entry point
│   └── sculptureData.jsx         # Sculpture collection data
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd sculpture-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to the URL shown in the terminal (typically `http://localhost:5173`)

## Available Scripts

- `npm run dev` - Start the development server with hot module replacement
- `npm run build` - Build the application for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## Usage

1. **Navigate**: Click the "Next" button to cycle through the sculpture collection
2. **View Details**: Click "Show details" to read about the sculpture's history and significance
3. **Hide Details**: Click "Hide details" to collapse the description
4. **Container Interaction**: Click on the container to see event propagation in action

## Key Concepts Demonstrated

- **State Management**: Using React hooks (`useState`) to manage component state
- **Event Handling**: Implementing click handlers with proper event propagation control
- **Conditional Rendering**: Dynamically showing/hiding content based on state
- **Component Composition**: Building reusable and maintainable components
- **Data Management**: Separating data concerns from UI logic

## Sculpture Collection

The app features sculptures including:
- Homenaje a la Neurocirugía by Marta Colvin Andrade
- Floralis Genérica by Eduardo Catalano
- Eternal Presence by John Woodrow Wilson
- Moai by Unknown Artist
- Blue Nana by Niki de Saint Phalle
- Ultimate Form by Barbara Hepworth
- And 6 more iconic works

## Development

This project uses Vite for fast development and building:

- **Hot Module Replacement (HMR)**: Changes reflect instantly without full page reload
- **Fast Refresh**: Preserves component state during development
- **Optimized Builds**: Production builds are optimized for performance

## Contributing

Feel free to submit issues or pull requests to improve the application or add more sculptures to the collection.

## License

This project is open source and available under the MIT License.
