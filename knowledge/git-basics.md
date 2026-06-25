# Git & GitHub — What just happened

## The one-sentence version

**Git** saves snapshots of your files over time. **GitHub** is where you store those snapshots online so they're safe, shareable, and accessible anywhere.

---

## Think of it like this

Imagine you're writing a book.

- **Git** = your personal revision history. Every time you finish a chapter, you take a "snapshot." You can always go back to any earlier version if you mess something up.
- **GitHub** = the publisher's server. You send your snapshots there so they're backed up online and others can see them.

Your files are the book. The snapshots are called **commits**. GitHub is the cloud shelf.

---

## What we actually did, step by step

### 1. `git init`
We told Git: *"start tracking this folder."*
The folder was: `ReadReadRead/`
Git created a hidden `.git` folder inside it — that's where all the history lives.

### 2. `git branch -m main`
By default Git names the first branch `master`. We renamed it to `main` — the modern standard.

A **branch** is like a parallel version of your project. You start with one (`main`). Later you can create more branches to test ideas without breaking the real thing.

### 3. `git add landing_page.html app_screens.html`
We told Git: *"include these two files in the next snapshot."*
This is called **staging** — you're picking what goes into the commit.

### 4. `git commit -m "Initial commit — landing page and app screen mockups"`
We took the snapshot. The `-m` is the message — a short note describing what changed.
This snapshot is now permanently saved in your local Git history.

### 5. `git remote add origin https://github.com/pattrickq/ReadReadRead.git`
We told Git: *"the online home for this project is at this GitHub URL."*
`origin` is just a nickname for that URL. You'll see it used everywhere.

### 6. `git push -u origin main`
We sent the snapshot to GitHub.
`push` = upload. `origin` = the GitHub URL. `main` = the branch we're sending.
The `-u` means "remember this connection so future pushes are just `git push`."

---

## The words you'll hear constantly

| Word | What it means |
|------|--------------|
| **repo** | Short for repository — your project folder tracked by Git |
| **commit** | A saved snapshot with a message |
| **branch** | A parallel version of the project |
| **main** | The primary branch — your "official" version |
| **push** | Upload commits to GitHub |
| **pull** | Download changes from GitHub to your local folder |
| **clone** | Copy a GitHub repo to your computer for the first time |
| **remote** | The online version (GitHub) of your repo |
| **origin** | The nickname Git uses for your GitHub remote |

---

## What to do next time we change a file

When Claude updates `landing_page.html` or `app_screens.html`, just say **"commit to git"** and these three commands run:

```bash
git add .
git commit -m "your message here"
git push
```

- `git add .` = stage everything that changed
- `git commit -m "..."` = snapshot with a message
- `git push` = send to GitHub

That's it. Three commands, every time.

---

## Your live links (GitHub Pages)

Once GitHub Pages is enabled, your files are live at:

- Landing page: `https://pattrickq.github.io/ReadReadRead/landing_page.html`
- App screens: `https://pattrickq.github.io/ReadReadRead/app_screens.html`

GitHub Pages reads your `main` branch and serves the HTML files as real websites. Any time you push a change, the live site updates automatically within ~1 minute.

---

## Why this matters for ReadReadRead

- Your work is **backed up** — not just on your Mac, also on GitHub
- You have a **history** — every commit is a version you can go back to
- You have **live shareable links** — send them to investors, designers, developers
- When you hire a developer, they `clone` the repo and start from exactly where you are
