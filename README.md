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

**Existing repo/folder:**

> ⚠️ Make sure your folder is empty or all important files are committed to Git before running. degit will overwrite any conflicting files.

```bash
npx degit arcanesandip/react-starter .
npm install
npm run dev
```

If the folder is not empty and you still want to proceed:

```bash
npx degit arcanesandip/react-starter . --force
```

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