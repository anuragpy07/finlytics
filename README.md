# Finlytics

**finlytics** is a modern AI-powered finance platform designed to help users make data-driven financial decisions. Built using the latest web technologies, finlytics combines intelligent analysis with a sleek user experience.

## 🚀 Features

- 🔐 **Authentication with Clerk** – Seamless and secure user authentication and session management.
- 📊 **AI-Driven Insights** – Use AI to get actionable insights from financial data.
- 🧾 **Form Handling** – Robust and reactive forms with validation using React Hook Form and Zod.
- 💾 **PostgreSQL with Supabase** – Modern backend infrastructure for storing user and financial data.
- 💅 **Elegant UI** – Built with **shadcn/ui** and **Tailwind CSS** for a clean, responsive interface.
- ⚡ **Next.js Framework** – High-performance SSR and optimized frontend routing.

## 🛠️ Tech Stack

| Layer        | Technology                     |
|--------------|--------------------------------|
| Frontend     | Next.js, React, Tailwind CSS   |
| UI Library   | shadcn/ui                      |
| Forms        | React Hook Form, Zod           |
| Auth         | Clerk                          |
| Database     | PostgreSQL via Supabase        |
| Styling      | Tailwind CSS                   |

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/finlytics.git
cd finlytics

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Add your Supabase and Clerk keys to the .env.local file

# Run the development server
npm run dev

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=

# Clerk
CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_FRONTEND_API=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up 
```

## 📦 Scripts
finlytics includes several npm scripts to streamline development, testing, and deployment:

| Command             | Description                                                  |
|---------------------|--------------------------------------------------------------|
| `npm run dev`       | Launches the development server on `localhost:3000`. Hot-reloads on file changes. |
| `npm run build`     | Compiles the application for production. Outputs static assets and server code in the `.next` directory. |
| `npm start`         | Starts the production server. Run `npm run build` first.     |
| `npm run lint`      | Runs ESLint across the codebase to identify and fix issues.  |
| `npm run format`    | Applies code formatting using Prettier (if configured).      |

These scripts help ensure consistency across local development, CI pipelines, and deployment environments.

---

## 🤝 Contributing

We welcome contributions from the community to improve and extend **finlytics**!

To contribute:

1. **Fork** the repository on GitHub.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/your-username/finlytics.git
   cd finlytics
3.Create a new branch
Always work in a separate branch for your changes:
```bash
git checkout -b feat/your-feature-name
```
4.Make your changes
Implement your feature or fix. Run the following commands to ensure code quality:
```bash
npm run lint
npm run format
```
5.Commit your changes
Stage and commit your code with a meaningful message:
```bash
git add .
git commit -m "feat: add your-feature-description"
```
6.Push your branch to GitHub
Push your local branch to your remote fork:
```bash
git push origin feat/your-feature-name
```
6.Open a Pull Request
Go to your forked repo on GitHub and click "Compare & pull request". Fill in a clear title and description, and submit your PR to the original repository’s main branch.

## ✅Contribution Guidelines
- Follow the project's code style and structure.
- Keep pull requests focused and concise.
- Include tests or screenshots where applicable.
- Use descriptive branch and commit names.
- Make sure your code passes lint and format checks.
Thank you for contributing to finlytics! 🚀

## License
This project is licensed under the MIT License. See the LICENSE file for details.


 
