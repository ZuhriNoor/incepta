# INCEPTA 2026 🚀

**A Premier Technical Festival focused on AI Agents & Generative AI**
*Organized by ASCA, College of Engineering, Trivandrum*

Welcome to the official repository for the **INCEPTA 2026** website. This project is a modern, responsive, and interactive web application built to showcase the events, competitions, and workshops of our upcoming tech fest.

## 🌟 Features

- **Immersive UI**: Stunning particle background effects using Three.js and warm, neon-themed aesthetics.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices.
- **Interactive Components**: Smooth animations, glassmorphism effects, and dynamic event overlays.
- **SPA Navigation**: Seamless page transitions using React Router (HashRouter for GitHub Pages compatibility).
- **Event Registration**: Complete registration system with payment integration.
- **Payment Gateway**: Razorpay integration for secure payment processing.
- **Email Confirmation**: Automated confirmation emails sent to registrants.
- **Modern Tech Stack**: Built with React 19, Vite, and Lucide React icons.

## 🛠️ Tech Stack

### Frontend
- **Framework**: React.js (Vite)
- **Styling**: Vanilla CSS (Custom design system)
- **3D Graphics**: Three.js (Particle background)
- **Routing**: React Router DOM
- **Icons**: Lucide React
- **Payment**: Razorpay Checkout

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Payment Gateway**: Razorpay
- **Email Service**: Nodemailer
- **Data Storage**: JSON files (easily migratable to database)

## 🚀 Getting Started

To run this project locally on your machine:

### Frontend Setup

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/ajmal-uk/incepta.git
    cd incepta
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Configure environment variables** (optional, for backend integration):
    Create a `.env` file in the root directory:
    ```env
    VITE_API_BASE_URL=http://localhost:3000/api
    ```

4.  **Run the development server**:
    ```bash
    npm run dev
    ```
    The app will be available at `http://localhost:5173`.

### Backend Setup

1.  **Navigate to server directory**:
    ```bash
    cd server
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Configure environment variables**:
    - Copy `.env.example` to `.env` (or create `.env` file)
    - Fill in your Razorpay credentials
    - Configure email settings (Gmail example provided)
    
    See `server/README.md` for detailed configuration instructions.

4.  **Start the backend server**:
    ```bash
    npm start
    # or for development with auto-reload
    npm run dev
    ```
    The server will run on `http://localhost:3000`.

### Full Stack Setup

To run both frontend and backend:

1. Open two terminal windows
2. In the first terminal, run the frontend:
   ```bash
   npm run dev
   ```
3. In the second terminal, run the backend:
   ```bash
   cd server
   npm run dev
   ```

## 📦 Deployment

This project is configured for automatic deployment to **GitHub Pages**.

To deploy a new version:
```bash
npm run deploy
```
This command builds the project (creating a `dist` folder) and pushes it to the `gh-pages` branch.

## 📝 Registration & Payment

The application includes a complete registration and payment system:

- **Registration Flow**: Users can register for events through dedicated registration pages
- **Payment Integration**: Secure payment processing via Razorpay
- **Email Confirmation**: Automatic confirmation emails sent upon successful registration
- **Registration Tracking**: All registrations are stored and can be retrieved

For detailed backend API documentation, see `server/README.md`.

## 🔗 Live Website

Visit the live site here: **[https://ajmal-uk.github.io/incepta](https://ajmal-uk.github.io/incepta)**

---
*Designed with ♥ by the ASCA Tech Team*