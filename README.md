# Typing Speed Test

A modern, React-based typing speed test application that helps users measure and improve their typing speed and accuracy.

## Features

- Real-time typing speed measurement (WPM - Words Per Minute)
- Accuracy tracking
- Multiple test durations (15s, 30s, 60s)
- Error tracking and visualization
- Dynamic word list that updates as you type
- Visual feedback for correct and incorrect words
- Ability to generate new word lists
- Responsive design

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository

```bash
git clone https://github.com/Tyrowin/typing-test
```

2. Navigate to the project directory

```bash
cd typing-speed-test
```

3. Install dependencies

```bash
npm install
```

4. Start the development server

```bash
npm run dev
```

5. Open your browser and visit `http://localhost:5173`

## How to Use

1. Select your preferred test duration using the buttons at the top
2. Click the input field and start typing
3. Type the words shown in the box above
4. Words turn:
   - Green when typed correctly
   - Red when typed with errors
   - Current word is underlined
5. Press space to move to the next word
6. Test automatically ends when the timer runs out
7. View your results:
   - Words Per Minute (WPM)
   - Accuracy percentage
   - Total errors
8. Click "Restart Test" to try again with a new word list

## Built With

- [React](https://reactjs.org/) - Frontend framework
- [Vite](https://vitejs.dev/) - Build tool
- CSS Modules - Styling

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the Apache License, Version 2.0 - see the LICENSE file for details.
