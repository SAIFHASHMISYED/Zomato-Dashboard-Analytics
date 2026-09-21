# GitHub Upload Guide

## Option 1 — GitHub website

1. Sign in to GitHub.
2. Select **New repository**.
3. Repository name:

```text
zomato-powerbi-analytics-dashboard
```

4. Add a description:

```text
Zomato restaurant analytics dashboard built in Power BI using the supplied Zomato Excel dataset.
```

5. Choose **Public** if this is intended for a portfolio.
6. Do not create an additional README because this repository already contains one.
7. Create the repository.
8. Select **Add file → Upload files**.
9. Upload the complete contents of this folder while preserving the folder structure.
10. Commit the files.

## Option 2 — Git command line

From the root of this repository:

```bash
git init
git add .
git commit -m "Add Zomato Power BI analytics dashboard"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/zomato-powerbi-analytics-dashboard.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

## Important

Keep these folders exactly as shown:

```text
powerbi/
data/
screenshots/
docs/
```

This keeps the repository organized and makes the README image paths work correctly.

## Verify after uploading

Open the GitHub repository and check that:

- The README displays both dashboard screenshots.
- The PBIX file is present under `powerbi/`.
- The Excel workbook is present under `data/`.
- Both screenshots are present under `screenshots/`.
- Documentation is present under `docs/`.
