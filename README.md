# QuickGPT

Here is an enhanced and attractive version of your project description, formatted perfectly for a GitHub README file.

-----

# 🤖 AI Content Hub - A Full-Stack MERN Project

Welcome to the **AI Content Hub**, a complete step-by-step tutorial project building a full-stack AI-powered application using the MERN stack (MongoDB, Express.js, React.js, Node.js).

This application allows users to sign up, purchase credits, and leverage the power of AI to generate both text-based content and stunning images from prompts.

[](https://opensource.org/licenses/MIT)
[](https://www.google.com/search?q=https://github.com/YOUR_USERNAME/YOUR_REPO/stargazers)
[](https://www.google.com/search?q=https://github.com/YOUR_USERNAME/YOUR_REPO/network/members)

*(Add a GIF of your application here\!)*

-----

## 🚀 Live Demo

Check out the live deployed application here: **[https://your-live-app-url.com](https://www.google.com/search?q=https://your-live-app-url.com)**

## ✨ Key Features

  * **Secure User Authentication**: JWT-based authentication for user registration and login.
  * **AI-Powered Text Generation**: Seamlessly interact with **Google's Gemini AI** to generate articles, summaries, code, and more.
  * **AI-Powered Image Generation**: Create unique images from text descriptions. Generated images are efficiently stored, optimized, and delivered via **ImageKit**.
  * **Credit-Based System**: Users can purchase credits through a secure online payment gateway (e.g., Stripe/Razorpay) to access AI features.
  * **Personalized User Dashboard**: Track credit balance, view generation history, and manage account settings.
  * **Modern & Responsive UI**: A sleek and intuitive user interface built with React.js and a modern styling library like Tailwind CSS.
  * **RESTful API**: A robust backend built with Node.js and Express.js, connected to a MongoDB database.

## 🛠️ Tech Stack

This project is built with the following technologies:

| Category      | Technology                                                                                                                              |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| **Frontend** |    |
| **Backend** |                                      |
| **Database** |                                                                                              |
| **AI Services** | **Google Gemini API** (for text), **Image Generation API** (e.g., Stability AI, DALL-E)                                                  |
| **Image Hosting** | **ImageKit** |
| **Payments** | **Stripe / Razorpay** |
| **Deployment** | **Vercel** (Frontend), **Render / Heroku** (Backend)                                                                                      |

## ⚙️ Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

  * Node.js (v18 or later)
  * npm / yarn
  * MongoDB (local instance or a cloud service like MongoDB Atlas)
  * API keys for Google Gemini, ImageKit, and your chosen Payment Gateway.

### Installation & Setup

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
    cd YOUR_REPO
    ```

2.  **Setup the Backend (`server`):**

    ```bash
    cd server
    npm install
    ```

    Create a `.env` file in the `server` directory and add the following variables:

    ```env
    # .env in server directory
    PORT=8080
    MONGO_URI="your_mongodb_connection_string"
    JWT_SECRET="your_super_secret_jwt_key"

    # Google Gemini API Key
    GEMINI_API_KEY="your_gemini_api_key"

    # ImageKit API Credentials
    IMAGEKIT_PUBLIC_KEY="your_imagekit_public_key"
    IMAGEKIT_PRIVATE_KEY="your_imagekit_private_key"
    IMAGEKIT_URL_ENDPOINT="your_imagekit_url_endpoint"

    # Payment Gateway API Keys (e.g., Stripe)
    STRIPE_SECRET_KEY="your_stripe_secret_key"
    ```

3.  **Setup the Frontend (`client`):**

    ```bash
    cd ../client
    npm install
    ```

    Create a `.env.local` file in the `client` directory and add the following variables:

    ```env
    # .env.local in client directory
    VITE_API_BASE_URL="http://localhost:8080/api/v1"

    # Payment Gateway Public Key (e.g., Stripe)
    VITE_STRIPE_PUBLISHABLE_KEY="your_stripe_publishable_key"
    ```

### Running the Application

1.  **Start the Backend Server:**
    From the `server` directory, run:

    ```bash
    npm run dev
    ```

    The server should now be running on `http://localhost:8080`.

2.  **Start the Frontend Development Server:**
    From the `client` directory, run:

    ```bash
    npm run dev
    ```

    The React application should now be running on `http://localhost:5173`.

## 🚀 Deployment

This application is designed to be easily deployed.

  * **Frontend (React App):** Deploy to a static hosting service like **Vercel**, **Netlify**, or **GitHub Pages**. Remember to set the environment variables in the build settings.
  * **Backend (Node.js/Express API):** Deploy to a service like **Render**, **Heroku**, or any cloud provider that supports Node.js applications.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

-----

\<p align="center"\>
Made with ❤️ by [Your Name]
\</p\>
\<p align="center"\>
Show your support by ⭐️ this repository\!
\</p\>
