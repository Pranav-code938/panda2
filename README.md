

An interactive 2D anime chibi animated birthday story set in a candlelit Hogwarts-inspired medical ward, featuring a Hufflepuff-scarf wizard panda postal courier, an evasive `IGNORE` button, an animated wax-seal unrolling sequence, and a cursive parchment scroll.

## Publishing to GitHub Pages (One-Click Branch Setup)

This project already includes a pre-built `docs/` folder with relative asset paths (`base: './'`) and `.nojekyll`, so GitHub Pages can serve it directly with zero GitHub Actions or extra build setup.

1. **Create and sync to a new GitHub repository** (for example, `dr-panda-birthday`) on the `main` branch.
2. Open your repository on GitHub and go to **Settings → Pages**.
3. Under **Build and deployment → Source**, keep **Deploy from a branch**.
4. Under **Branch**, select **`main`** and **`/docs`**, then click **Save**.
5. Wait ~30–60 seconds and refresh **Settings → Pages**—your live webpage link (`https://<your-username>.github.io/<your-repo-name>/`) will appear at the top.

## Editing the Letter Later

The birthday letter lives in `src/data/letter.ts`. If you ever edit it later, rebuild the `docs/` folder before pushing to GitHub:

```bash
npm install
npm run build
```

## Local Development

```bash
npm install
npm run dev
```
