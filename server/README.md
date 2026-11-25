# API server

Express, Sequelize and PostgreSQL. Part of [KidsyBook](../README.md).

> **Structure only.** The source code is private. Source files here are intentionally empty so you can see how the project is organized. Commands describe the private codebase.

## Responsibilities

- Accounts, email verification and child profiles
- Story text and image generation services
- Live progress with Socket.IO
- PDF production
- Credits, packages and online payment
- Administration and statistics

## Main dependencies

`@google/genai`, `@google/generative-ai`, `@sparticuz/chromium`, `@tailwindcss/vite`, `axios`, `bcrypt`, `body-parser`, `compression`, `cors`, `dotenv`, `express`, `express-rate-limit`, `helmet`, `jsonwebtoken`, `mime-types`, `moment`, `moment-timezone`, `multer`, `node-cron`, `nodemailer`, `pdfkit`, `pg`, `puppeteer`, `puppeteer-core`, `sequelize`, `socket.io`, `stripe`, `tailwindcss`, `validator`, `xss`

## Structure

```text
config/                           1 file
controllers/                      6 files
middlewares/                      7 files
models/                           8 files
routes/                           5 files
scripts/                          1 file
services/                         10 files
util/                             5 files
```

## Commands

```bash
npm install
npm start
```
