Guess My Number
A React Native mobile game where you pick a number and your opponent tries to guess it!
🎮 Features

Interactive Gameplay — Pick a number between 1-99 and challenge your opponent to guess it
Smart Feedback — Get "Higher" or "Lower" hints after each guess
Round Tracking — See how many guesses it takes to find your number
Beautiful UI — Modern, colorful design with smooth animations
Android & iOS Support — Works on both platforms


Node.js (v14 or higher)
npm or yarn
Expo CLI (npm install -g expo-cli)
Android Emulator or iOS Simulator (or physical device)

Installation

Clone the repository

bashgit clone https://github.com/Nilesh07x/GuessNumberGame.git
cd GuessNumberGame

Install dependencies

bashnpm install

Start the development server

bashnpx expo start

Run on your device


Android: Press a in the terminal or scan QR code with Expo Go app
iOS: Press i in the terminal or scan QR code with Expo Go app
Physical Device: Download Expo Go from App Store/Play Store and scan the QR code

📁 Project Structure
GuessNumberGame/
├── screens/
│   ├── StartGameScreen.js      # Initial number input screen
│   ├── GameScreen.js           # Main guessing gameplay
│   └── GameOverScreen.js       # Results screen
├── components/
│   └── ui/
│       ├── PrimaryButton.js    # Reusable button component
│       ├── Title.js            # Title text component
│       ├── Card.js             # Card container component
│       └── InstructionText.js  # Instruction text component
├── constants/
│   └── colors.js               # Color theme definitions
├── App.js                       # Main app component
└── package.json
🎯 How to Play

Start Game — Enter a number between 1-99 and confirm
Opponent Guesses — The app makes guesses
Provide Feedback — Tell if the guess is "Higher" or "Lower"
Win/Lose — Game ends when the number is guessed
See Results — View how many rounds it took

🛠️ Technologies Used

React Native — Cross-platform mobile development
Expo — Easy React Native setup and deployment
React Hooks — State management with useState
Styling — React Native StyleSheet

🐛 Troubleshooting
Buttons showing "?" instead of text
This is usually a font rendering issue on Android. Try:
bashnpx react-native start --reset-cache
npx react-native run-android
Or update the buttonText style in PrimaryButton.js:
javascriptbuttonText: {
  color: 'white',
  textAlign: 'center',
  fontSize: 16,
  fontWeight: '700',
  fontFamily: 'System',
},
App won't start
Clear node modules and reinstall:
bashrm -rf node_modules package-lock.json
npm install
npx expo start --reset-cache
📝 License
This project is open source and available under the MIT License.
👤 Author
Nilesh — GitHub
🤝 Contributing
Contributions are welcome! Feel free to:

Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📧 Support
If you have any questions or issues, feel free to open an issue on GitHub or contact me directly.
🌟 Show your support
Give a ⭐️ if this project helped you!
