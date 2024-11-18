# DashFi - Finance Dashboard App

The **DashFi** is a modern tool for managing invoices and expenses, providing secure, optimized, and user-friendly functionality. Built with cutting-edge technologies, it ensures performance, accessibility, and scalability.

LIVE: [DashFi](https://dash-fi.vercel.app/)
---

## 🚀 Features

- Tracking of invoices and expenses.
- Secure user authentication with encrypted passwords.
- Optimized performance using debouncing.
- Accessibility-focused and responsive design.
- Schema-based data validation for secure operations.

---

## 🛠️ Tech Stack

- **Frontend & Backend**: [Next.js](https://nextjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Database**: [Vercel PostgreSQL](https://vercel.com/docs/storage/postgresql)
- **Data Validation**: [Zod](https://zod.dev/)
- **Authentication**: [NextAuth](https://next-auth.js.org/)
- **Encryption**: [Bcrypt](https://www.npmjs.com/package/bcrypt)
- **Performance Optimization**: [use-debounce](https://www.npmjs.com/package/use-debounce)
- **Accessibility and Linting**: ESLint

---

## ⚙️ Installation and Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/finance-dashboard.git
   cd finance-dashboard

2.   **Install Dependencies**
    pnpm install

3. **Configure Environment Variables**

    Create a .env.local file and add the following:

        DATABASE_URL=your_postgresql_database_url
        NEXTAUTH_SECRET=your_nextauth_secret
        NEXTAUTH_URL=http://localhost:3000

4. **Run the Development Server**

    npm run dev

    Open your browser and navigate to http://localhost:3000.

## 🛠️ Scripts

    Start Development: npm run dev
    Lint Code: npm run lint
    Build for Production: npm run build
    Run Production Build: npm start
    
## Home
![alt text](/public/home.png)

## Dashboard
![alt text](/public/image.png)

## Invoices
![alt text](/public/image-1.png)

## Create Invoice
![alt text](/public/image-2.png)

## Edit Invoice
![alt text](/public/image-3.png)


## Login
![alt text](/public/image-4.png)