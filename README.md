# AI-Powered Virtual Try-On System

A revolutionary in-store shopping experience that allows customers to virtually try on clothes using AI and 3D technology.

## Features

### Customer Experience
- 3D Body Scanning & Model Creation
- Smart Display Try-On
- Personalized AI Recommendations
- Gesture-Based Interaction
- Multilingual Support

### Retailer/Admin Features
- Inventory Management
- Real-Time Clothing Overlay
- AI-Driven Sales Insights
- Dynamic Pricing & Promotions
- Customer Tracking & Loyalty Programs

## Tech Stack

- Frontend: Next.js, React, Three.js (for 3D rendering)
- Backend: Node.js, Express
- Database: MongoDB
- AI/ML: TensorFlow.js, MediaPipe
- Authentication: JWT
- 3D Processing: Three.js, WebGL

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd virtual-try-on
```

2. Install dependencies:
```bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

3. Set up environment variables:
```bash
# Frontend (.env.local)
NEXT_PUBLIC_API_URL=http://localhost:5000
NEXT_PUBLIC_3D_MODEL_API_URL=http://localhost:5000/api/3d-models

# Backend (.env)
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Start the development servers:
```bash
# Start backend server
cd backend
npm run dev

# Start frontend server
cd frontend
npm run dev
```

## Project Structure

```
virtual-try-on/
├── frontend/                 # Next.js frontend application
│   ├── components/          # Reusable React components
│   ├── pages/              # Next.js pages
│   ├── public/             # Static assets
│   └── styles/             # CSS styles
├── backend/                 # Node.js/Express backend
│   ├── controllers/        # Route controllers
│   ├── models/            # Database models
│   ├── routes/            # API routes
│   └── services/          # Business logic
└── docs/                   # Documentation
```

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details. 