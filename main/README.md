# Sacred Spaces (DarshanEase)

Sacred Spaces (DarshanEase) is a comprehensive Temple Darshan Booking Platform built using the MERN (MongoDB, Express, React, Node.js) stack. It simplifies the process of booking Darshan slots, managing temple information, and handling donations.

## 🚀 Features

- **User Authentication**: Secure JWT-based login and registration.
- **Temple Management**: Detailed views for various temples with photo galleries and descriptions.
- **Slot Booking**: Intuitive interface for booking Darshan slots for specific dates and times.
- **User Dashboard**: Track your bookings, donations, and profile information.
- **Admin Dashboard**: Manage temples, slots, and view platform analytics.
- **Responsive Design**: Mobile-friendly UI built with Tailwind CSS and shadcn/ui.

## 🛠️ Tech Stack

- **Frontend**: React, Vite, TypeScript, Tailwind CSS, shadcn/ui, React Router, Lucide Icons.
- **Backend**: Node.js, Express, Mongoose (MongoDB ODM), JWT, Bcrypt.js.
- **Database**: MongoDB.

## 📦 Project Structure

```text
sacred-spaces-render-main/
├── frontend/             # React + Vite client application
│   ├── src/              # Source code (Components, Pages, Services)
│   └── package.json      # Frontend dependencies and scripts
└── server/               # Node.js + Express API server
    ├── models/           # Mongoose schemas
    ├── routes/           # API endpoints
    ├── controllers/      # Route logic
    └── .env              # Environment variables
```

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+)
- [MongoDB](https://www.mongodb.com/try/download/community) installed and running locally.

### Setup Instructions

1. **Clone the repository**:
   ```sh
   git clone <repository-url>
   cd sacred-spaces-render-main
   ```

2. **Backend Setup**:
   ```sh
   cd server
   npm install
   # Create a .env file based on the requirements below
   npm run dev
   ```

3. **Frontend Setup**:
   ```sh
   cd ../frontend
   npm install
   npm run dev
   ```

### Environment Variables

Create a `.env` file in the `server` directory:

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/darshanease
JWT_SECRET=your_jwt_secret_key
```

## 🌐 Usage

- **Frontend**: [http://localhost:8080](http://localhost:8080)
- **Backend API**: [http://localhost:5000](http://localhost:5000)

## 📄 License

This project is licensed under the ISC License.
