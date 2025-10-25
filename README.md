# Authentication App

A modern React authentication system with multiple auth flows built with Vite and TailwindCSS.

## Live Demo

🚀 **Live URL:** https://auth-742.netlify.app

## Features

- User Registration
- User Login
- Forgot Password
- OTP Verification
- Responsive Design with TailwindCSS
- Client-side Routing with React Router

## Tech Stack

- **React** 19.1.1
- **Vite** 7.1.7
- **React Router DOM** 7.9.4
- **TailwindCSS** 4.1.15
- **ESLint** for code quality

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- pnpm package manager

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd authtication

# Install dependencies
pnpm install
```

### Development

```bash
# Start development server
pnpm dev
```

The app will be available at `http://localhost:5173`

### Build

```bash
# Build for production
pnpm build

# Preview production build
pnpm preview
```

## Routes

- `/` - Registration (default)
- `/login` - User login
- `/register` - User registration
- `/forgot-password` - Password reset
- `/otp` - OTP verification

## Project Structure

```
src/
├── pages/                        # Authentication pages
│   ├── Login.jsx
│   ├── Register.jsx
│   ├── ForgotPassword.jsx
│   └── OTP.jsx
├── routes/                      # Router configuration
├── layout/                      # Layout components
├── components/                  # Shared components
└── assets/                      # Static assets
```

## Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm preview` - Preview production build
- `pnpm lint` - Run ESLint

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.
