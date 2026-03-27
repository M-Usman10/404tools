# 404tools.dev — The tools you were actually looking for.

A growing collection of fast, focused developer utilities. No bloat, no accounts, no cost. Just tools.

🔗 **[404tools.dev](https://404tools.dev)**

---

## What is this?

404tools.dev is a free, open-source hub of developer tools built for speed and simplicity. Every tool does one thing well. No login required, no tracking, no paywalls.

---

## Tools

| Tool | Description | Status |
|------|-------------|--------|
| [Cron Vision](https://404tools.dev/cron) | Visualize any cron expression — heatmap, next runs, plain English | ✅ Live |
| Regex Tester | Test and explain regular expressions in plain English | 🚧 Coming soon |
| JWT Decoder | Decode and inspect JWT tokens instantly | 🚧 Coming soon |
| JSON Formatter | Format, validate and diff JSON | 🚧 Coming soon |
| SQL Generator | Describe your query in plain English, get SQL | 🚧 Coming soon |
| UUID Generator | Generate UUIDs in bulk, multiple formats | 🚧 Coming soon |

---

## Philosophy

- **No login** — Use any tool instantly. No accounts, no email, no friction.
- **No bloat** — Every tool does one thing. Nothing more.
- **No cost** — Free forever. Always.
- **No backend** — Most tools are pure frontend. Fast, private, client-side.

---

## Tech stack

- **Framework** — Next.js / React
- **Styling** — Tailwind CSS
- **Deployment** — Vercel
- **Domain** — 404tools.dev

---

## Running locally

```bash
# Clone the repo
git clone https://github.com/yourusername/404tools.dev.git
cd 404tools.dev

# Install dependencies
npm install

# Start the dev server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Project structure

```
404tools.dev/
├── app/
│   ├── page.tsx          # Homepage
│   ├── cron/
│   │   └── page.tsx      # Cron Vision tool
│   └── layout.tsx
├── components/
│   ├── Navbar.tsx
│   ├── ToolCard.tsx
│   └── Footer.tsx
├── public/
└── README.md
```

---

## Contributing

Want to add a tool or improve an existing one? Contributions are welcome.

1. Fork the repo
2. Create a branch: `git checkout -b tool/your-tool-name`
3. Build your tool in `app/your-tool-name/`
4. Submit a pull request with a short description

**Guidelines for new tools:**
- Pure frontend preferred — no backend dependencies
- One tool, one purpose — no feature creep
- Mobile responsive
- No external tracking or analytics inside tools

---

## Suggesting a tool

Have an idea for a tool? [Open an issue](https://github.com/yourusername/404tools.dev/issues/new) with the label `tool suggestion` and describe what it should do.

---

## License

MIT — free to use, fork, and build on.

---

<p align="center">Built for developers, by developers · <a href="https://404tools.dev">404tools.dev</a></p>
