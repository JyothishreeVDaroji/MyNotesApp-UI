# MyNotesApp UI

A simple front-end notes application built with HTML and CSS.

## Getting Started

### Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/)

### Setting Up VS Code

This repository includes a `.vscode/` folder with recommended extensions and settings to get you productive quickly.

#### How to Enable GitHub Copilot in VS Code

1. **Install VS Code** – Download and install from [code.visualstudio.com](https://code.visualstudio.com/).

2. **Install GitHub Copilot** – Open VS Code, go to the **Extensions** view (`Ctrl+Shift+X` / `Cmd+Shift+X`), search for **GitHub Copilot**, and click **Install**.

3. **Sign in to GitHub** – After installing, click the GitHub Copilot icon in the status bar (bottom right) and sign in with your GitHub account. You need an active [GitHub Copilot subscription](https://github.com/features/copilot).

4. **Accept workspace recommendations** – When you open this project, VS Code will prompt you to install the recommended extensions (including GitHub Copilot). Click **Install All** to install them automatically.

5. **Verify it's working** – Open any `.html` or `.css` file and start typing. GitHub Copilot will suggest code completions inline. Press `Tab` to accept a suggestion.

#### Recommended Extensions (auto-configured)

| Extension | Purpose |
|---|---|
| `GitHub.copilot` | AI-powered code completions |
| `GitHub.copilot-chat` | Chat with Copilot inside VS Code |
| `esbenp.prettier-vscode` | Auto-format HTML & CSS on save |
| `ritwickdey.LiveServer` | Live-reload preview in the browser |

### Running the App

1. Open the project folder in VS Code.
2. Right-click `login.html` in the Explorer and select **Open with Live Server**.
3. The app will open in your browser at `http://127.0.0.1:5500/login.html`.

## Project Structure

```
MyNotesApp-UI/
├── index.html       # Registration page
├── login.html       # Login page
├── dashboard.html   # Notes dashboard
├── style.css        # Shared stylesheet
└── .vscode/
    ├── extensions.json  # Recommended VS Code extensions
    └── settings.json    # VS Code workspace settings
```
