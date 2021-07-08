# Web Repository Template

This template provides an improved web development experience when using Visual Studio Code and GitHub. It includes configurations for settings, extensions, and a GitHub Pages workflow.

## How to Use

### ⚙️ Setup

1. Click [Use this template](https://github.com/ansipes/mejo-web-template) and create the repository from template
2. Under `Settings` -> `Pages` pick `gh-pages` as the branch and `/ (root)` as the folder, the click save
3. Clone your repository and open in Visual Studio Code
4. Open the Extensions panel in Visual Studio Code
   - Search for `@recommended`
   - Under `WORKSPACE RECOMMENDATIONS` click `Install Workspace Extension Recommendations` (cloud with a down arrow)

### 🌐 Preview

Click the "Go Live" button in the bottom right of Visual Studio Code. This will open [http://127.0.0.1:5500/](http://127.0.0.1:5500/) in your browser.

Everything in your `src` folder will be served just like it is on a real web server.

### 🎉 Publish

As long as you have enabled GitHub Pages, your project should be published at [https://{{ USERNAME }}.github.io/{{ REPOSITORY }}](#).

Replace `{{ USERNAME }}` with your GitHub username. Replace `{{ REPOSITORY }}` with your repository name.

## What's Included

### Settings

This template includes settings that improve writing and version control in Visual Studio Code.

#### ✏️ Writing

These settings solve common problems like unsaved work, poorly formatted code, and missing brackets.

- Save on Focus Change
- Format Code on Save
- Close Brackets Automatically

#### 🗃 Version Control

These settings help simplify sending your code to GitHub by reducing three steps (add, commit, push) to a single step. Simply type a commit message in the Source Control view and click the checkmark.

- Stage Changes Automatically
- Push After Commit

### Extensions

This template includes recommended extensions that improve testing and formatting in Visual Studio Code.

#### 🌐 Live Server

- Serve the `src` directory on [localhost:5500](localhost:5500)
- Refresh Browser on Save

#### 🪄 Prettier

- Format Code with Opinionated Rules

#### 🔎 HTMLHint

- Analyze HTML for Problems

### Workflows

This template includes a workflow that improves deployment on GitHub.

### 🚀 Deploy

- Copy `src` to the `gh-pages` branch
