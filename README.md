# 🐾 Project Name
> One line describing what the project does and what problem it solves.

![Project Status](https://img.shields.io/badge/status-active-6DB33F?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-0077B5?style=flat-square)

---

## 📌 About

Write 2-3 sentences here explaining:
- **What** the project is
- **Who** it's for
- **Why** it exists (what problem it solves)

**Example:**
> PetSched is a SaaS platform built for veterinary clinics to manage appointments, patient records, and client relationships — all in one place. Built to replace scattered spreadsheets and WhatsApp messages with a centralized, easy-to-use system.

---

## ✨ Features

- ✅ Feature 1 — short description
- ✅ Feature 2 — short description
- ✅ Feature 3 — short description
- 🚧 Feature 4 — in development

---

## 🚀 Demo

🔗 **Live:** [yourproject.com.br](https://yourproject.com.br)

<!-- Add a screenshot or GIF here — this is the most important part -->
<!-- Tip: use https://www.screentogif.com/ to record a GIF of the interface -->

![App Screenshot](./docs/screenshot.png)

---

## 🛠️ Tech Stack

**Front-end**
- [Next.js 14](https://nextjs.org/) — React framework
- [Tailwind CSS](https://tailwindcss.com/) — styling
- [TypeScript](https://www.typescriptlang.org/) — type safety

**Back-end**
- [Java 17 + Spring Boot 3](https://spring.io/projects/spring-boot) — REST API
- [Spring Security + JWT](https://spring.io/projects/spring-security) — authentication
- [PostgreSQL](https://www.postgresql.org/) — database
- [Prisma ORM](https://www.prisma.io/) — database layer

**Infrastructure**
- [Docker](https://www.docker.com/) — containerization
- [AWS EC2 + S3](https://aws.amazon.com/) — cloud deployment
- [GitHub Actions](https://github.com/features/actions) — CI/CD pipeline

---

## ⚙️ Getting Started

### Prerequisites

- Node.js 18+
- Java 17+
- Docker
- PostgreSQL

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Luc4sF01/project-name.git

# 2. Navigate to the project
cd project-name

# 3. Install dependencies
npm install

# 4. Set up environment variables
cp .env.example .env
# Edit .env with your credentials

# 5. Run with Docker
docker-compose up -d

# 6. Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🗄️ Database

```bash
# Run migrations
npx prisma migrate dev

# Seed with sample data
npx prisma db seed
```

---

## 🌍 Environment Variables

Create a `.env` file based on `.env.example`:

```env
# Database
DATABASE_URL="postgresql://user:password@localhost:5432/dbname"

# Authentication
JWT_SECRET="your-secret-key"
JWT_EXPIRES_IN="7d"

# AWS (optional)
AWS_ACCESS_KEY_ID="your-access-key"
AWS_SECRET_ACCESS_KEY="your-secret"
AWS_BUCKET_NAME="your-bucket"
```

---

## 📁 Project Structure

```
src/
├── app/                  # Next.js pages and routes
│   ├── (auth)/           # Authentication pages
│   ├── dashboard/        # Protected dashboard
│   └── api/              # API routes
├── components/           # Reusable UI components
├── lib/                  # Utilities and configs
├── hooks/                # Custom React hooks
└── types/                # TypeScript type definitions
```

---

## 🧪 Tests

```bash
# Run unit tests
npm run test

# Run with coverage
npm run test:coverage
```

---

## 📬 Contact

Built by **Lucas Filipe Santos Lima**

[![Portfolio](https://img.shields.io/badge/Portfolio-lucasfsl.com.br-0F3460?style=flat-square)](https://lucasfsl.com.br)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-lucas--filipe--santos-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/lucas-filipe-santos)
[![Email](https://img.shields.io/badge/Email-lucashfilipe@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:lucashfilipe@gmail.com)

---

<div align="center">
  <sub>If this project helped you, consider giving it a ⭐</sub>
</div>
