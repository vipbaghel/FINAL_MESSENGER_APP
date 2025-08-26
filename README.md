
# AMA Message App

A modern AMA (Ask Me Anything) message application built with Next.js, TypeScript, Tailwind CSS, and MongoDB. Users can sign up, send messages, and verify their email addresses. The app features authentication, message management, and a clean UI.

## Features

- User authentication (sign up, sign in, email verification)
- Send and receive messages
- Responsive UI with Tailwind CSS
- MongoDB integration
- API routes for backend logic
- Email verification using Resend

## Folder Structure

```
ama-app/
├── emails/                # Email templates (e.g., VerificationEmail)
├── public/                # Static assets
├── src/
│   ├── app/               # Next.js app directory (routing, layout, pages)
│   ├── components/        # React components (MessageCard, Navbar, UI)
│   ├── context/           # React context providers (AuthProvider)
│   ├── helpers/           # Helper functions (sendVerificationEmail)
│   ├── lib/               # Library files (dbConnect, resend, utils)
│   ├── model/             # Mongoose models (User)
│   ├── schemas/           # Validation schemas (Zod)
│   ├── types/             # TypeScript types
│   ├── messages.json      # Sample messages data
│   ├── middleware.ts      # Middleware for Next.js
├── .env                   # Environment variables
├── package.json           # Project dependencies and scripts
├── tailwind.config.js     # Tailwind CSS configuration
├── tsconfig.json          # TypeScript configuration
└── README.md              # Project documentation
```

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm or yarn
- MongoDB database

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/ama-message-app.git
    cd ama-app
    ```

2. Install dependencies:
    ```sh
    npm install
    # or
    yarn install
    ```

3. Set up environment variables:
    - Copy `.env.example` to `.env` and fill in your MongoDB URI and Resend API key.

### Running the App

```sh
npm run dev
# or
yarn dev
```

- The app will be available at [http://localhost:3000](http://localhost:3000).

## Scripts

- `dev` - Start development server
- `build` - Build for production
- `start` - Start production server
- `lint` - Run ESLint

## Technologies Used

- Next.js
- TypeScript
- Tailwind CSS
- MongoDB & Mongoose
- Resend (email service)
- Zod (validation)

## License

This project is licensed under the MIT License.

---

Feel free to contribute or open
