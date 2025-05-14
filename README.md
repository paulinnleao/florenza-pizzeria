# 🍕 Pizzeria Florenza - Full-Stack Management System

![Project Banner](https://via.placeholder.com/1200x400/222222/FFFFFF?text=Pizzeria+Florenza) 
*(Replace with your actual banner image)*

A complete pizza restaurant management system with online ordering, real-time tracking, and admin dashboard.

## 🚀 Features

### Customer Facing
- 🖥️ Interactive menu with pizza customization
- 🛒 Cart & checkout system
- 📱 Responsive design (mobile-first)
- 🔍 Real-time order tracking (WebSocket)
- 🤖 Configurable FAQ chatbot

### Admin Panel
- 📊 Order management dashboard
- 🧾 Inventory control
- 👥 Employee role system (admin/operator)
- 📝 Dynamic menu management
- 📈 Sales analytics

## 🛠️ Tech Stack

### Frontend
- **Next.js 14** (App Router)
- **TypeScript**
- **Tailwind CSS** + shadcn/ui
- **React Hook Form** + Zod validation
- **TanStack Query** (React Query)
- **Socket.IO Client**

### Backend
- **NestJS** (Node.js framework)
- **PostgreSQL** + Prisma ORM
- **REST API** + WebSocket
- **JWT Authentication**

### DevOps
- **Vercel** (Frontend hosting)
- **Railway** (Backend hosting)
- **GitHub Actions** (CI/CD)
- **Jest** (Testing)

## 📦 Installation

1. Clone the repository:
```bash
  git clone https://github.com/yourusername/florenza-pizzeria.git
```

2. Install dependencies:
```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install
```

3. Set up environment variables:
```bash
# Frontend .env.local
NEXT_PUBLIC_API_URL=http://localhost:3001
# ... other variables

# Backend .env
DATABASE_URL="postgresql://..."
JWT_SECRET="your_secret_here"
# ... other variables
```

4. Run the development servers:
```bash
# Frontend
cd frontend
npm run dev

# Backend (in another terminal)
cd backend
npm run start:dev
```

## 🌐 Project Structure
```bash
florenza-pizzeria/
├── frontend/          # Next.js application
│   ├── app/           # App router
│   ├── components/    # UI components
│   └── lib/           # Utilities
│
├── backend/           # NestJS application
│   ├── src/           # Source files
│   │   ├── auth/      # Authentication
│   │   ├── orders/    # Order management
│   │   └── ...        # Other modules
│   └── prisma/        # Database schema
│
└── README.md          # This file
```

## 🤝 Contributing
We welcome contributions! Please follow these steps:

1. Fork the project
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some amazing feature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See LICENSE for more information.

h3. 📧 Contact

Your Name - @yourtwitter - your.email@example.com

Project Link: https://github.com/yourusername/florenza-pizzeria

### Customization Tips:
1. Replace placeholder images with actual screenshots
2. Add your actual contact information
3. Include real deployment URLs when available
4. Add badges (build status, coverage, etc.) if applicable
5. Consider adding a "Demo" section with GIFs/videos

Would you like me to add any specific sections or modify the existing ones? 😊
