# 👕 Clothora – AI-Powered Fashion Design Platform

Clothora is an AI-powered fashion design and e-commerce platform that enables users to generate custom clothing designs using Generative AI, personalize products, manage orders, and complete purchases through a modern and responsive web application.

Built with Next.js, TypeScript, PostgreSQL, Clerk Authentication, and Google Gemini AI, Clothora combines fashion and artificial intelligence to provide a unique clothing customization experience.

---

## ✨ Features

### 🎨 AI Clothing Design Generation

* Generate unique clothing designs using AI prompts
* Multiple design variations for each request
* AI-powered prompt refinement
* Real-time design preview

### 👤 User Authentication

* Secure sign up and login
* User profile management
* Clerk authentication integration
* Protected routes and user sessions

### 🛍️ Shopping Experience

* Browse fashion products
* Add products to cart
* Manage wishlist
* Custom clothing selection

### 📦 Order Management

* Shipping address management
* Checkout workflow
* Order history tracking
* Order status monitoring

### 👨‍💼 Admin Dashboard

* Manage products
* View customer orders
* Monitor platform activity
* Administrative controls

### 📱 Responsive Design

* Mobile-first design
* Tablet and desktop support
* Modern UI with Tailwind CSS
* Smooth user experience

---

## 🏗️ Tech Stack

### Frontend

* Next.js 15
* React 18
* TypeScript
* Tailwind CSS
* Redux Toolkit
* React Query

### Authentication

* Clerk Authentication

### Database

* PostgreSQL

### AI Integration

* Google Gemini AI
* Genkit AI Framework

### UI Components

* Radix UI
* Lucide React Icons
* Recharts

### Deployment

* Vercel (Recommended)

---

## 📂 Project Structure

```bash
src/
├── actions/           # Server actions
├── ai/                # AI flows and Genkit configuration
├── app/               # Next.js App Router pages
├── components/        # Reusable UI components
├── config/            # Application configuration
├── hooks/             # Custom React hooks
├── lib/               # Database and utility functions
├── providers/         # Context providers
├── redux/             # Redux store configuration
└── types/             # TypeScript definitions
```

---

## 🚀 Getting Started

### Prerequisites

* Node.js 18+
* npm or yarn
* PostgreSQL Database
* Clerk Account
* Google AI API Key

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/clothora.git

cd clothora
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env.local` file in the root directory:

```env
# PostgreSQL
DATABASE_URL=your_postgresql_connection_string

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_publishable_key
CLERK_SECRET_KEY=your_secret_key

# Google Gemini AI
GOOGLE_API_KEY=your_google_api_key

# Clerk URLs
NEXT_PUBLIC_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_AFTER_SIGN_UP_URL=/
```

### 4. Run Development Server

```bash
npm run dev
```

Application will be available at:

```bash
http://localhost:9002
```

---

## 🤖 AI Features

### Generate Clothing Designs

Users can:

1. Enter a clothing design prompt
2. Refine prompts using AI assistance
3. Generate multiple design concepts
4. Preview AI-generated fashion designs
5. Customize and save designs

Example Prompt:

```text
Modern oversized black hoodie with neon blue cyberpunk graphics and futuristic typography.
```

---

## 🗄️ Database

The application uses PostgreSQL for:

* User information
* Orders
* Addresses
* Product data
* Wishlist management

Database connection is managed through:

```bash
src/lib/db.ts
```

---

## 📜 Available Scripts

```bash
# Development
npm run dev

# Production Build
npm run build

# Start Production Server
npm run start

# Type Checking
npm run typecheck

# AI Development
npm run genkit:dev

# AI Development with Watch Mode
npm run genkit:watch
```

---

## 🔒 Security Features

* Secure authentication with Clerk
* Protected API routes
* Environment variable protection
* PostgreSQL SSL support
* Session management

---

## 🌟 Future Enhancements

* Payment Gateway Integration
* AR Virtual Try-On
* Product Recommendations
* Fashion Trend Analysis
* Social Sharing Features
* Multi-Vendor Marketplace
* AI Outfit Suggestions

---

## 👨‍💻 Author

Developed as an AI-powered fashion customization platform using modern web technologies and Generative AI.

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful, please give it a star on GitHub.
