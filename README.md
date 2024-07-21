<<<<<<< HEAD
# AI Interview Mocker

AI Interview Mocker is a web app to help users practice and improve their interview skills using AI. Built with Next.js, Drizzle ORM, Neon DB, Clerk, and Gemini API.

## Features

- AI-driven interview simulations
- User authentication with Clerk
- Data management with Drizzle ORM and Neon DB
- Integration with Gemini API
- Responsive UI with Next.js

## Tech Stack

- **Next.js**
- **Drizzle ORM**
- **Neon DB**
- **Clerk**
- **Gemini API**

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/ai-interview-mocker.git
   cd ai-interview-mocker
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env.local` file and add:

   ```env
   NEXT_PUBLIC_CLERK_FRONTEND_API=<your-clerk-frontend-api>
   CLERK_API_KEY=<your-clerk-api-key>
   GEMINI_API_KEY=<your-gemini-api-key>
   NEON_DATABASE_URL=<your-neon-database-url>
   ```

4. **Run the development server:**

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the app.

## Usage

1. Sign up or log in with Clerk.
2. Start a mock interview.
3. Review and get feedback on your responses.

## Contributing

1. Fork the repo.
2. Create a branch (`git checkout -b feature/your-feature-name`).
3. Make changes and commit (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

---
