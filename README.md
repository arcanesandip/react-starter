# react-starter

Personal React + Tailwind starter. Clone and build.

## What's inside

- Vite + React
- Tailwind CSS v4
- ESLint (flat config) + Prettier
- Absolute imports (`@/`)
- Folder structure ready to go

## Usage

**New project:**
```bash
npx degit arcanesandip/react-starter my-new-project
cd my-new-project
npm install
npm run dev
```

> Update `"name"` in `package.json` and `package-lock.json` to your project name.

**Existing repo/folder:**

> ⚠️ `--force` will overwrite any conflicting files in the folder. Make sure all important files are committed to Git before running.

```bash
npx degit arcanesandip/react-starter . --force
npm install
npm run dev
```

> Update `"name"` in `package.json` and `package-lock.json` to your project name.

## Environment variables

`.env.example` is committed to the repo — it has the variable names but no real values. It's just a template.

Copy it to `.env` and fill in your actual values:

```bash
cp .env.example .env
```

> `.env` is your local file only — it holds real values and is already in `.gitignore` so it never gets committed.

## Folder structure

```
src/
├── assets/
├── components/
│   └── ui/
├── hooks/
├── layouts/
├── pages/
└── utils/
```
