# Auto-Compiled LaTeX CV

Auto-compiled CV using GitHub Actions. Push changes to `cv.tex` and get a PDF automatically.

## Usage

### 1. Enable Workflow Permissions
Go to **Settings** → **Actions** → **General**

Under "Workflow permissions":
- Select **Read and write permissions**
- Check **Allow GitHub Actions to create and approve pull requests**
- Click **Save**

### 2. Edit Your CV
Edit `cv.tex` with your information, then push:

```
git add cv.tex
git commit -m "Update CV"
git push
```

### 3. Check Build Status
Go to **Actions** tab to see workflow status:
- ✅ Green = Success
- ⏳ Yellow = Running
- ❌ Red = Failed (check logs)

After first successful run, a `build` branch is created automatically.

### 4. Enable GitHub Pages
Go to **Settings** → **Pages**

Under "Build and deployment":
- Source: **Deploy from a branch**
- Branch: **build**
- Folder: **/ (root)**
- Click **Save**

### 5. Access Your CV
Your PDF will be live at:
```
https://yourusername.github.io/repo-name/
```

Inspo
https://github.com/sb2nov/resume
https://github.com/Erik-Cupsa/ResumeTemplate
https://github.com/jitinnair1/autoCV