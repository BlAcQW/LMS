# Project Setup Documentation

## Server Setup

### Prerequisites
- Node.js installed
- MongoDB running
- PayPal developer account and credentials

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>

2. Navigate to the server folder:
   ```bash
   cd server
3. Navigate to the server folder:
   ```bash
   npm install
4. Set up environment variables: Create a .env :
   ```bash
- CLIENT_URL=
- PORT=5000
- MONGO_URI=
- CLOUDINARY_CLOUD_NAME = "here"
- CLOUDINARY_API_KEY = "here"
- CLOUDINARY_API_SECRET = "here"
- PAYPAL_CLIENT_ID=
- PAYPAL_SECRET_ID=

5. **Start the server**:
   ```bash
   nodemon server


## Client Setup

### Prerequisites
- React with Vite
- Tailwindcss

1. Navigate to the server folder:
   ```bash
   cd client
2. Navigate to the server folder:
   ```bash
   npm install
3. Start the server:
   ```bash
   npm run dev 



