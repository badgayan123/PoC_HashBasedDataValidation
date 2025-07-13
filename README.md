# Secure Hash Generator

A modern, web-based application for generating SHA-256 hashes and managing passwords securely. Built with HTML, CSS, and JavaScript, this tool provides a user-friendly interface for cryptographic operations.

## 🚀 Features

### Hash Message Generator
- **SHA-256 Hashing**: Generate secure SHA-256 hashes from any text input
- **Copy to Clipboard**: One-click hash copying functionality
- **Real-time Processing**: Instant hash generation as you type

### Password Manager
- **Secure Storage**: Store password hashes locally
- **Password Verification**: Verify passwords against stored hashes
- **Password Visibility Toggle**: Show/hide password fields for convenience
- **Hash Display**: View and copy stored password hashes

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with responsive design
- **Icons**: Font Awesome 6.0
- **Typography**: Google Fonts (Inter)
- **Hashing**: SHA-256 cryptographic algorithm

## 📁 Project Structure

```
pythonProject5_Hashing/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── hasher.py           # Python hashing utilities
├── main.py             # Python main application
├── notes.txt           # Project notes
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start using the application immediately

### Usage

#### Hash Message
1. Click on the "Hash Message" tab
2. Enter your message in the text area
3. Click "Generate Hash" to create a SHA-256 hash
4. Use the copy button to copy the hash to your clipboard

#### Password Manager
1. Click on the "Password Manager" tab
2. **Set Password**:
   - Enter your password
   - Click "Store Password Hash" to save the hash
3. **Verify Password**:
   - Re-enter your password in the verification field
   - Click "Verify Password" to check if it matches

## 🔒 Security Features

- **SHA-256 Algorithm**: Industry-standard cryptographic hashing
- **Client-side Processing**: All hashing happens locally in your browser
- **No Data Transmission**: Your data never leaves your device
- **Secure Storage**: Passwords are stored as hashes, never as plain text

## 🎨 UI/UX Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern Interface**: Clean, professional design with smooth animations
- **Tab Navigation**: Easy switching between hash generation and password management
- **Visual Feedback**: Clear success/error messages and loading states
- **Accessibility**: Proper labels, ARIA attributes, and keyboard navigation

## 🔧 Customization

The application is built with modular CSS and JavaScript, making it easy to customize:

- **Styling**: Modify `styles.css` to change colors, fonts, and layout
- **Functionality**: Extend `script.js` to add new features
- **Icons**: Replace Font Awesome icons with your preferred icon set

## 📝 Notes

- This is a client-side application - no server required
- All data is stored locally in your browser
- For production use, consider implementing additional security measures
- The Python files (`hasher.py`, `main.py`) provide backend hashing capabilities

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- SHA-256 algorithm implementation
- Font Awesome for icons
- Google Fonts for typography
- Modern web standards and best practices

---

**Built with ❤️ for secure cryptographic operations** 