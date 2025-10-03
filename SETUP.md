# Setup Guide

This guide will help you push your DevOps Bootcamp Portfolio to GitHub.

## 📝 Initial Setup

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the **"+"** icon in the top right → **"New repository"**
3. Repository settings:
   - **Repository name:** `devops-bootcamp-portfolio` (or your preferred name)
   - **Description:** "Portfolio showcasing my DevOps Bootcamp projects"
   - **Visibility:** Public (recommended for portfolio)
   - **DO NOT** initialize with README, .gitignore, or license (we already have these)
4. Click **"Create repository"**

### 2. Initialize Git and Push to GitHub

Open your terminal in the portfolio directory and run:

```bash
# Navigate to portfolio directory
cd C:\Users\CanerIskenderoglu\programming\devops-bootcamp-portfolio

# Initialize Git repository
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: DevOps Bootcamp Portfolio"

# Add GitHub remote (replace YOUR-REPO-URL with the URL from step 1)
git remote add origin https://github.com/caner404/devops-bootcamp-portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## 🔗 Updating Project Links

### To add your Docker project link:

1. Open `README.md`
2. Find the line: `🔗 **Repository:** [Add your Docker project link here]`
3. Replace with: `🔗 **Repository:** [Your Docker Project](https://github.com/caner404/your-docker-repo)`

### Example:

```markdown
🔗 **Repository:** [Docker Bootcamp Project](https://github.com/caner404/docker-bootcamp)
```

## 📦 Adding New Projects

As you complete new bootcamp projects:

1. Move the project from "Upcoming" to "In Progress" or "Completed"
2. Add the repository link
3. Update the status badge

### Example of moving a project to completed:

```markdown
### ✅ Completed Projects

#### 2. Jenkins CI/CD

> **Status:** Completed ✓

Implementation of continuous integration and continuous deployment pipelines using Jenkins.

**Technologies:** Jenkins, CI/CD, Pipeline as Code

🔗 **Repository:** [Jenkins CI/CD Project](https://github.com/caner404/jenkins-cicd)
```

## 🔄 Regular Updates

After making changes to your README:

```bash
# Add changes
git add .

# Commit with a descriptive message
git commit -m "Update: Added Docker project link"

# Push to GitHub
git push
```

## 💡 Tips

- **Keep the README updated** as you progress through the bootcamp
- **Add detailed descriptions** to each project repository
- **Include screenshots** or diagrams in individual project READMEs
- **Update the "Last Updated" date** in the main README when making changes
- **Star your own repository** to make it easy to find

## 🌐 Portfolio URL

After pushing to GitHub, your portfolio will be available at:

```
https://github.com/caner404/devops-bootcamp-portfolio
```

You can share this URL on your resume, LinkedIn, or anywhere you want to showcase your DevOps skills!

## 🎯 Next Steps

1. ✅ Initialize Git and push to GitHub
2. ✅ Add your Docker project link
3. ✅ Share your portfolio on LinkedIn
4. ✅ Keep it updated as you complete new projects
5. ✅ Consider adding GitHub Pages for a website version (optional)

---

**Happy coding and good luck with your DevOps Bootcamp! 🚀**
