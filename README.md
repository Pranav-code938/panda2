

An interactive 2D anime chibi animated birthday story set in a candlelit Hogwarts-inspired medical ward, featuring a Hufflepuff-scarf wizard panda postal courier, an evasive `IGNORE` button, an animated wax-seal unrolling sequence, and a cursive parchment scroll.

## Publishing to GitHub Pages (After AI Studio Sync)

1. Sync your project to GitHub (`main` branch).
2. In your GitHub repository, open **Settings → Pages**.
3. Under **Build and deployment → Source**, select **GitHub Actions** (do **not** use *Deploy from a branch*, because Vite builds the site during deployment).
4. Open the **Actions** tab:
   - If **Deploy to GitHub Pages** is already listed, click **Run workflow** (or wait for it to finish).
   - If the **Actions** tab does not show **Deploy to GitHub Pages** (because AI Studio Sync omits hidden `.github` folders), click **Add file → Create new file** in your repository, name it `.github/workflows/deploy.yml`, paste the contents of `.github/workflows/deploy.yml` from this project, and click **Commit changes**.
5. Once the workflow finishes with a green checkmark, your live webpage URL (`https://<your-username>.github.io/<your-repo-name>/`) appears in **Settings → Pages**.

## Editing the Letter Later

The birthday letter lives in `src/data/letter.ts`. Update it and sync/push to GitHub—GitHub Actions will automatically rebuild and redeploy the site.

## Local Development

```bash
npm install
npm run dev
```
