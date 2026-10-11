# LEGOCRAFT — AI-Powered Artisan Marketplace

**Empowering Rural Artisans Through Digital Commerce**

LEGOCRAFT is an online marketplace designed to connect rural artisans with customers. It helps artisans showcase handmade products, manage their shops, and reach more buyers through digital technology and AI-powered features.

## ✨ Features

### 🛍️ Buyer Features
- Browse and search handmade products.
- Explore products by category and keyword.
- View product details and add items to the cart.
- Place orders with Cash on Delivery.
- Track order history and status.
- Discover products through the interactive **Build Your Craft** quiz.

### 🧑‍🎨 Seller Features
- Register and log in using the available registration options.
- Create and manage product listings.
- Upload product images.
- Use AI-assisted product title and description generation.
- Enhance product images using the AI photo studio.
- Create product listings using multilingual voice input.
- Get AI-assisted dynamic pricing suggestions.
- Manage orders and update their status.

### 🔐 Admin Features
- View marketplace statistics.
- Manage users and ban or unban accounts.
- Remove product listings.
- View marketplace orders.

## 🛠️ Technologies Used

- **Frontend:** HTML, Tailwind CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Data Storage:** Local JSON file
- **Additional Tools:** AI-assisted product tools and image processing
- **Mobile Project:** Android wrapper using Capacitor

## 📁 Project Structure

```text
legocraft-main/
├── android/          # Android application project
├── public/           # Website pages and frontend assets
├── lib/              # Server-side helper modules
├── data/              # Application data
├── proc image/        # Project image-processing assets
├── server.mjs         # Express server and API routes
├── package.json       # Dependencies and scripts
├── .env.example       # Environment configuration template
└── README.md          # Project documentation
```

## 🚀 Installation and Setup

### Prerequisites
- Node.js 18 or later
- npm

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/Codewithsempai/legocraft.git
   ```

2. Open the project folder:

   ```bash
   cd legocraft
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. If required, copy `.env.example` to `.env` and configure the environment variables.

5. Start the application:

   ```bash
   npm start
   ```

6. Open your browser at:

   `http://localhost:3000`

> Check `package.json` for the exact start command and port configured for your version of the project.

## 🌐 Deployment

LEGOCRAFT requires a Node.js-compatible hosting service because it uses an Express backend and API routes. Deploy the complete application to a service that supports Node.js, and configure its environment variables as required.

**Important:** GitHub Pages alone cannot run the Express backend. Use GitHub to store the source code and a compatible hosting platform to run the application.

## 🔒 Security Notes

- Configure production credentials and environment variables securely.
- Never commit real passwords, API keys, or secrets to GitHub.
- Change demo credentials before deploying publicly.
- Review authentication, file uploads, and data persistence before production use.

## 🎯 Project Objective

To empower rural artisans by providing an accessible digital marketplace where they can showcase their creativity, connect with customers, and grow their businesses using modern web technologies.

## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for details.

---

**LEGOCRAFT — Connecting Creativity, Culture, and Customers.**
