# pyshiny-01-express-basic
Basic Shiny for Python (PyShiny) app using Shiny Express

## Before

1. Join GitHub
2. Install Git
3. Confiure Git user.name and user.email
4. Install current Python
5. Install VS Code Editor
6. Install VS Code Extension: [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
7. Install VS Code Extension: [Shiny](https://marketplace.visualstudio.com/items?itemName=posit.shiny-python)
8. Install VS Code Expension: [Pyright](https://marketplace.visualstudio.com/items?itemName=ms-pyright.pyright)

## Browser: Start a new GitHUb Project with Default Files

1. Open browser and log in to GitHub
2. Create a new repo (e.g., pyshiny-01-express-basic) with Default README.md and .gitignore (Python).

## Local Machine: Clone down and set up project

1. Open VS Code.
2. Clone Git repo into Documents folder.

## Local Machine: Set Up Project Virtual Environment

Open your project folder in VS Code. Open a VS Code terminal (PowerShell or Bash or zsh) using Terminal / New Terminal.

1. Upgrade pip and install wheel.
2. Create local project virtual environment.
3. Activate the local project virtual environment.
4. Install packages into active environment.
5. Freeze to requirements.txt (see example in this repo).
6. Document your workflow and commands in your README.md.
7. Add file: pyrightconfig.json (see example in this repo).

Example Terminal Commands: Windows - record your process in your README.md:

```Powershell
py -m pip install --upgrade pip wheel
py -m venv .venv
.\.venv\Scripts\Activate.ps1
py -m pip install --upgrade shiny htmltools
py -m pip freeze > requirements.txt
```

Example Terminal Commands: Mac/Linux - record your process in your README.nd:

```bash
python3 -m pip install --upgrade pip wheel
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip wheel
python3 -m pip freeze > requirements.txt
```

## Create A Basic Shiny Express App

1. In VS Code with your project folder open, create a new file app.py in the root project folder.
2. See the example in this repo.
3. In the terminal window, run the app with the following command.

```Powershell
shiny run app.py
```

## References

- [Shiny Express](https://shiny.posit.co/blog/posts/shiny-express/)
- [Shiny for Python - main](https://shiny.posit.co/py/)
