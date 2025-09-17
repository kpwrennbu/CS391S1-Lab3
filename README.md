Got it 👍 — here’s the full **README.md** formatted so you can copy-paste directly:

````markdown
# Next.js + GitHub Demo

This demo shows how to create a new Next.js app, connect it to a GitHub repository, and practice common Git commands (init, commit, push, branching).

---

## 1. Create a New Next.js App
Make sure you have **Node.js** and **npm** installed.

```bash
npx create-next-app@latest my-app
cd my-app
````

---

## 2. Create an Empty GitHub Repository

1. Go to [GitHub](https://github.com) and click **New Repository**.
2. Name it something like:

   ```
   [firstInitial][lastName]-Demo
   ```

   Example: `kwrenn-Demo`
3. Leave it **blank** (no README, no .gitignore).

---

## 3. Initialize Git Locally

Inside your `my-app` folder:

```bash
git init
git branch -M main
git remote add origin https://github.com/[your-username]/[repo-name].git
```

---

## 4. First Commit & Push

```bash
git add .
git commit -m "Initial Next.js app setup"
git push -u origin main
```

---

## 5. Create a Feature Branch

```bash
git checkout -b feature-demo
```

Make a small change in `app/page.tsx` or `pages/index.js` (like editing text or adding a button).

Stage, commit, and push the branch:

```bash
git add .
git commit -m "Add feature button"
git push origin feature-demo
```

---

## 6. Open a Pull Request

1. Go to your GitHub repo.
2. You’ll see a banner to open a Pull Request for `feature-demo`.
3. Click **Compare & pull request** and submit it.

---

