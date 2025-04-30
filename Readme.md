# 🌟 Building My Portfolio with MkDocs

In this guide, we will use **MkDocs** to build a professional portfolio. MkDocs is a static site generator specifically designed for project documentation. It is written in Python and uses the Jinja2 templating engine to generate HTML pages from Markdown files. MkDocs is simple, efficient, and perfect for creating and maintaining documentation for your projects.

📖 Official documentation: [MkDocs Documentation](https://www.mkdocs.org/)

---

## 🚀 Steps to Build Your Portfolio

### 1️⃣ Install MkDocs

First, create a Python environment and install MkDocs:

```bash
conda create -n mkdocs python=3.8 -y
conda activate mkdocs
pip install mkdocs
```

---

### 2️⃣ Create a New MkDocs Project

Generate a new MkDocs project and navigate into the project directory:

```bash
mkdocs new my_portfolio
cd my_portfolio
```

---

### 3️⃣ Run the Development Server

Start the development server to preview your site locally:

```bash
mkdocs serve
```

💡 **Tip:** To specify a custom port and host, use:

```bash
mkdocs serve -a 127.0.0.1:8811
```

---

### 4️⃣ Customize the `mkdocs.yml` Configuration File

Edit the `mkdocs.yml` file to configure your site settings, such as the site name, theme, and navigation structure. For example:

```yaml
site_name: My Portfolio
theme:
    name: material
nav:
    - Home: index.md
    - Projects: projects.md
    - About: about.md
```

---

### 5️⃣ Add Content to Your Pages

Create and edit Markdown files in the `docs` directory to add content to your portfolio. For example:

- `index.md` for the homepage
- `projects.md` for showcasing your projects
- `about.md` for your personal information

---

### 6️⃣ Build the Project

Generate the static files for your project:

```bash
mkdocs build
```

---

### 7️⃣ Initialize a Git Repository

Set up version control for your project:

```bash
git init
```

---

### 8️⃣ Create a Repository on GitHub

Link your local repository to a remote GitHub repository:

```bash
git remote add origin https://github.com/username/repo.git
```

---

### 9️⃣ Add Files to the Git Repository

Stage all files for the initial commit:

```bash
git add .
```

---

### 🔟 Commit the Changes

Save your changes with a meaningful commit message:

```bash
git commit -m "Initial commit"
```

---

### 1️⃣1️⃣ Set the Default Branch

Set the default branch to `master` (or `main`):

```bash
git branch -M main
```

---

### 1️⃣2️⃣ Push Changes to GitHub

Upload your project to the remote repository:

```bash
git push -u origin main
```

---

### 1️⃣3️⃣ Install MkDocs Plugins

Enhance your MkDocs project with useful plugins:

```bash
pip install mkdocs-material
pip install mkdocs-git-revision-date-localized-plugin
pip install mkdocs-material-extensions
pip install mkdocs-git-authors-plugin
```

---

### 1️⃣4️⃣ Add a Custom Domain (Optional)

If you have a custom domain, create a `CNAME` file in the `docs` directory with your domain name:

```text
www.yourdomain.com
```

---

### 1️⃣5️⃣ Deploy the Project

Deploy your project to GitHub Pages:

```bash
mkdocs gh-deploy
```

---

### 1️⃣6️⃣ Deploy to a Specific Branch

If you want to deploy to a specific branch, use:

```bash
mkdocs gh-deploy --remote-branch your_branch_name
```

---

### 1️⃣7️⃣ Test Your Deployment

Visit your GitHub Pages URL to ensure your portfolio is live and functioning as expected. The URL is typically:

```
https://<username>.github.io/<repository-name>/
```

---

🎉 **Congratulations!** You have successfully built and deployed your portfolio using MkDocs. Customize your site further to make it truly yours! 🚀