# SIH Team Manager

SIH team/project calling-order manager.

## Features

- Every spreadsheet submission is preserved as a separate project entry.
- Team name, leader, semester, project topic, contact information, members, and submitted details.
- Click a team to expand the complete record.
- Leader **Call** button when a phone number is available.
- Drag and drop teams to change the running order.
- **Complete** marks the entire team card green; **Absent** marks the entire team card red.
- Search and status filtering.
- Night-mode interface using the **Roboto** font.
- Current order and status are saved in the browser.

## Push directly from terminal

After extracting this project, open PowerShell/Terminal inside the project folder:

```bash
git init
git branch -M main
git add .
git commit -m "Initial SIH Team Manager"
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your GitHub username and repository name.

### GitHub CLI shortcut

If GitHub CLI is installed and authenticated:

```bash
gh repo create YOUR-REPOSITORY --public --source=. --remote=origin --push
```

## GitHub Pages

After pushing: **GitHub → Repository → Settings → Pages → Deploy from a branch → main → / (root) → Save**.

GitHub will show the Pages URL.

## Updating the data

The team/project data is embedded in `index.html`. If the source spreadsheet changes, regenerate/update the page so the new submissions appear.
