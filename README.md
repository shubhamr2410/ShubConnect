

# ShubConnect

[](https://www.google.com/search?q=https://github.com/shubhamr2410/ShubConnect/stargazers)
[](https://www.google.com/search?q=https://github.com/shubhamr2410/ShubConnect/blob/main/LICENSE)
[](https://shub-connect.vercel.app/)

### **Live Demo: [shub-connect.vercel.app](https://shub-connect.vercel.app/)**

## 📖 About

ShubConnect is a modern, full-stack social media app built with Next.js. It features a sleek UI with Tailwind CSS and a robust backend to provide a complete social media experience.

## ✨ Features

  * **🔐 User Authentication:** Secure sign-up and sign-in with Clerk.
  * **✍️ Post Management:** Full CRUD (Create, Read, Update, Delete) functionality for posts.
  * **❤️ Social Interactions:** Like and comment on posts to engage with others.
  * **🔔 Notifications:** Real-time notifications for likes and comments.
  * **👤 Profile Customization:** Users can personalize their profiles.
  * **🎨 Sleek UI:** A modern and responsive design crafted with Tailwind CSS.

## 🛠️ Tech Stack

  * **Framework:** [Next.js](https://nextjs.org/)
  * **UI/Styling:** [Tailwind CSS](https://tailwindcss.com/)
  * **Database:** [PostgreSQL](https://www.postgresql.org/) via [Neon](https://neon.tech/)
  * **ORM:** [Prisma](https://www.prisma.io/)
  * **Authentication:** [Clerk](https://clerk.com/)
  * **File Uploads:** [UploadThing](https://uploadthing.com/)
  * **Deployment:** [Vercel](https://vercel.com/)

## 🚀 Getting Started

Follow these instructions to set up a local development environment.

### Prerequisites

  * Node.js (v18 or later)
  * npm or yarn
  * A PostgreSQL database instance (you can get one for free from [Neon](https://neon.tech/))

### Installation & Setup

1.  **Clone the repository:**

    ```sh
    git clone https://github.com/shubhamr2410/ShubConnect.git
    cd ShubConnect
    ```

2.  **Install dependencies:**

    ```sh
    npm install
    ```

3.  **Set up environment variables:**
    Create a `.env.local` file in the root directory and add your credentials.

    ```env
    # Clerk Authentication
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

    # Database (Get the connection string from Neon)
    DATABASE_URL=

    # UploadThing for File Uploads
    UPLOADTHING_SECRET=
    UPLOADTHING_APP_ID=

    # Base URL for your local environment
    NEXT_PUBLIC_BASE_URL=http://localhost:3000
    ```

4.  **Sync the database schema:**
    Push the Prisma schema to your database to create the tables.

    ```sh
    npx prisma db push
    ```

5.  **Run the development server:**

    ```sh
    npm run dev
    ```

Your application should now be running on [http://localhost:3000](https://www.google.com/search?q=http://localhost:3000).

## ☁️ Deployment

This project is deployed on **Vercel**. Vercel provides a seamless deployment experience for Next.js applications. To deploy your own version, simply fork this repository and connect it to your Vercel account.
