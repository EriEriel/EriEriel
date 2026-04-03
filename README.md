# Hi, I'm Pond

Self-taught developer based in Thailand, ~4 months into serious full-stack development. Enrolled in a CS program, but most of what I know comes from building things and reading docs. Chasing a junior full-stack role and eventually working in Japan.

I like understanding *why* things work, not just copying patterns that happen to compile.

---

## Currently building

### [Terminal Shelf](https://github.com/yourusername/terminal-shelf) *(deploying soon)*
A personal library tracker for books and fanfiction. Not a CRUD tutorial — this one had real problems.

**Stack:** Next.js 15 · Auth.js v5 · Prisma 7 · PostgreSQL · Tailwind · shadcn/ui

A few things that were actually hard:
- OAuth account linking across providers (GitHub + Google) — hit `OAuthAccountNotLinked` and had to dig into how Auth.js resolves account identity at the session layer
- Prisma 7's new driver adapter architecture — a breaking change from v6, most StackOverflow answers are wrong now
- Server Actions replacing REST routes — rethinking the data flow model, not just swapping fetch calls

---

### [kilo-c](https://github.com/yourusername/kilo-c)
A terminal text editor built from scratch in C, following the Kilo tutorial but understanding every line. Manual memory management, raw terminal I/O, gap buffer logic. This project is what made low-level systems click for me.

---

## Stack

**Day-to-day web work**
- TypeScript · Next.js 15 (App Router) · React · Tailwind · shadcn/ui
- Prisma · PostgreSQL
- Auth.js v5 · JWT

**Systems / lower-level**
- C (text editor, manual memory management)
- Rust (reading the book, starting projects — `wc` clone → key-value store path)

**Tooling**
- Arch Linux · Hyprland · Neovim · Ghostty · lazygit
- Git workflow: rebase over merge, linear history

---

## What I'm working toward

Right now, the immediate goal is getting Terminal Shelf deployed — a live URL is the thing I need before I start applying seriously. After that: writing a proper README with screenshots, documenting a hard technical problem I solved, then job applications.

Longer term: I want to go deep on systems programming (C → Rust path), and eventually work in Japan. Studying Japanese alongside everything else.

I also run small-group remote programming sessions for teenagers — Python, project-driven curriculum (Mad Libs → number guessing → text adventures). Teaching something is the fastest way to find out what you don't actually understand.

---

## Learning philosophy

I use AI as a last resort for blockers, not a first stop. When I do use generated code, I rewrite it from scratch so I understand what it's doing. I keep a personal `Coding_Docs` directory of Markdown notes — bug reports, learning summaries — that I actually go back to.

CS fundamentals matter to me more than framework churn. I read the Rust book cover-to-cover before writing a line of Rust, not because I had to, but because I wanted the mental map first.

---

## Contact

Open to junior full-stack roles. If you're building something interesting and want someone who will actually read the docs — let's talk.

- 📧 your@email.com
- 💼 [LinkedIn](https://linkedin.com/in/yourprofile)
