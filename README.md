

---

# Gym App with React and Vite ⚛️🏋️

This project is a simple gym-tracking app built with **React** and **Vite**, providing fast development and optimal Hot Module Replacement (HMR). The setup includes ESLint for code quality and supports both **@vitejs/plugin-react** and **@vitejs/plugin-react-swc** plugins for Fast Refresh.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Available Plugins](#available-plugins)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Technologies Used](#technologies-used)
7. [Contributing](#contributing)
8. [License](#license)

## Features

- **HMR with Vite**: Super-fast updates using Hot Module Replacement.
- **Exercise Library**: Browse, add, and track gym exercises.
- **Set & Rep Tracking**: Log each set, including reps and weights.
- **Goal Management**: Define and monitor workout goals.
- **ESLint Rules**: Code quality and consistency maintained with ESLint.
- **Lightweight Build**: Optimized for speed and minimal dependencies.

## Installation

Follow these steps to set up the project locally.

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/gym-app.git
   cd gym-app
   ```

2. **Install Dependencies**  
   Make sure to have Node.js and npm installed, then install all necessary dependencies:
   ```bash
   npm install
   ```

3. **Run the Development Server**
   Start the Vite server with HMR:
   ```bash
   npm run dev
   ```

4. **Linting**
   Run ESLint to check for code quality issues:
   ```bash
   npm run lint
   ```

5. **Build for Production**
   Compile and minify the app for production:
   ```bash
   npm run build
   ```

## Available Plugins

This project can use either of the following official plugins for React with Vite:

- **@vitejs/plugin-react**: Uses **Babel** for Fast Refresh.
- **@vitejs/plugin-react-swc**: Uses **SWC** for faster, more efficient Fast Refresh.

### Selecting a Plugin

By default, this setup uses `@vitejs/plugin-react`. To switch to the SWC version:

1. Uninstall `@vitejs/plugin-react` if installed:
   ```bash
   npm uninstall @vitejs/plugin-react
   ```

2. Install the SWC plugin:
   ```bash
   npm install @vitejs/plugin-react-swc
   ```

3. Update `vite.config.js`:
   ```javascript
   import react from '@vitejs/plugin-react-swc';

   export default {
     plugins: [react()],
   };
   ```

## Usage

Once set up, you can use the app to:

- **Add and Edit Exercises**: Manage your list of exercises.
- **Track Sets and Reps**: Log each set with details on reps and weights.
- **View Workout History**: See past sessions to monitor improvements.
- **Set Personal Goals**: Define goals for specific exercises or routines.



## Technologies Used

- **Vite**: Fast, modern build tool optimized for HMR.
- **React**: JavaScript library for building user interfaces.
- **ESLint**: Linting tool to maintain code quality.
- **Optionally**: Babel or SWC for Fast Refresh.

## Contributing

To contribute to this project:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Make and commit your changes.
4. Push to your fork and submit a pull request.

Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

