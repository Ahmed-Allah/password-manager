# 🔐 Secure Password Manager

A modern, secure password manager built with React and Convex, featuring password generation, security checks, and real-time synchronization.

![Password Manager](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-blue)
![React](https://img.shields.io/badge/React-19.0.0-61dafb)
![Convex](https://img.shields.io/badge/Convex-1.21.1-ff69b4)

## ✨ Features

- **🛡️ Secure Password Generation**: Create strong, unique passwords based on customizable criteria
- **🔍 Password Security Check**: Verify if passwords have been compromised in data breaches
- **🔄 Real-time Synchronization**: Instant updates across devices using Convex backend
- **🌓 Dark/Light Mode**: Comfortable viewing experience in any lighting condition
- **📱 Responsive Design**: Works seamlessly on desktop and mobile devices
- **🔒 Secure Authentication**: Email/password and anonymous authentication options

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/password-manager.git
   cd password-manager
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env.local` file in the root directory
   - Add your Convex URL:
     ```
     VITE_CONVEX_URL=your_convex_url_here
     ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## 🏗️ Tech Stack

- **Frontend**:
  - React
  - TypeScript
  - Tailwind CSS
  - Lucide Icons
  - Radix UI Components

- **Backend**:
  - Convex (Backend as a Service)
  - Real-time Data Sync
  - Secure Authentication

## 🔧 Project Structure

```
password-manager/
├── convex/              # Backend logic and database schema
├── src/                 # Frontend source code
│   ├── components/      # React components
│   ├── hooks/          # Custom React hooks
│   └── styles/         # CSS and styling files
└── public/             # Static assets
```

## 🛡️ Security Features

- Password strength validation
- Integration with HaveIBeenPwned API
- Secure password generation algorithms
- Real-time data encryption
- Secure authentication flow

## 🌟 Usage

1. **Sign In/Sign Up**:
   - Create an account using email/password
   - Or use anonymous authentication

2. **Generate Password**:
   - Enter required information
   - Get a secure, randomly generated password
   - Download password as a text file

3. **Check Password Security**:
   - Enter any password to check
   - Get instant feedback on password security
   - View number of times password appeared in data breaches

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## 📞 Support

For support, email [your-email@example.com] or open an issue in the repository.

---
Built with ❤️ using [Convex](https://convex.dev) and [React](https://reactjs.org)
