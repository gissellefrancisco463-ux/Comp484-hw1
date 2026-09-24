# Guide: Publishing Your Website with GitHub Pages

You will deploy your assignments live to the web using **GitHub Pages**, update your repository's `README.md` with the live URL, and submit your repository link.

---

## Table of Contents

1. [Prerequisites & Repository Check](#1-prerequisites--repository-check)
2. [Enabling GitHub Pages](#2-enabling-github-pages)
3. [Finding Your Live Site URL](#3-finding-your-live-site-url)
4. [Updating Your README.md](#4-updating-your-readmemd)
5. [What and How to Submit](#5-what-and-how-to-submit)
6. [Common Troubleshooting Tips](#6-common-troubleshooting-tips)

---

## 1. Prerequisites & Repository Check

Before enabling GitHub Pages, verify the following:

- **Repository Visibility:** Make sure your repository is set to **Public**. GitHub Pages is free for public repositories on standard student/free accounts.
- **Entry File:** Your main HTML entry point must be named **`index.html`** (all lowercase) and located in the **root** folder of your repository.
- **Relative File Paths:** Check that all file links in your HTML/CSS/JS (e.g., stylesheets, images, scripts) use relative paths (e.g., `./style.css` or `css/style.css`, **not** `/style.css` or local machine paths like `C:\Users\...` or `/Users/...`).

---

## 2. Enabling GitHub Pages

Follow these step-by-step instructions in your web browser:

1. Navigate to your project's GitHub repository page:
   ```text
   https://github.com/<your-username>/<your-repo-name>
   ```
2. Near the top navigation bar of your repository (below the repo title), click on **Settings** (gear icon ⚙️).
3. On the left sidebar menu, look under the **Code and automation** section and click on **Pages**.
4. Under **Build and deployment**:
   - **Source:** Ensure **Deploy from a branch** is selected in the dropdown.
   - **Branch:**
     - Select your default branch (usually `main` or `master`).
     - Leave the folder selector set to **`/(root)`**.
5. Click **Save**.

---

## 3. Finding Your Live Site URL

1. After saving, GitHub will queue an automated build action to publish your site.
2. Refresh the **Pages** settings tab after about 1–2 minutes.
3. Once the build completes, a banner will appear at the top of the **GitHub Pages** page displaying:
   > **"Your site is live at https://`<your-username>`.github.io/`<your-repo-name>`/"**
4. Click the link to test your live website in a new tab:
   - Ensure your styles (`.css`), images, and scripts (`.js`) load properly without errors.

---

## 4. Updating Your `README.md`

You must document your live site link inside your repository's `README.md` file so anyone viewing your code can visit the live application.

1. Open your repository's `README.md` file
2. Add a **Live Demo** section near the top of the file using Markdown syntax:

```markdown
# Project Name

A brief description of your project and what it does.

## 🚀 Live Demo

You can view the published website here:
[Live Website on GitHub Pages](https://<your-username>.github.io/<your-repo-name>/)
```

3. If editing locally:
   - Save your changes.
   - Commit and push to GitHub:
4. If editing directly on GitHub:
   - Scroll down, write a commit message like `docs: add live site link to README`, and click **Commit changes**.

---

## 5. What and How to Submit

For this assignment, you will submit the **Git clone URL (`.git`)** of your repository to Canvas/your learning management system.

### How to copy your `.git` link:

1. Go to the main page of your GitHub repository (`https://github.com/<your-username>/<your-repo-name>`).
2. Click the green **`<> Code`** button.
3. Under the **HTTPS** tab, click the copy icon 📋 next to the URL.
4. The link will end with `.git` and look like this:
   ```text
   https://github.com/<your-username>/<your-repo-name>.git
   ```
5. Paste this exact link into the assignment submission text box.

---
