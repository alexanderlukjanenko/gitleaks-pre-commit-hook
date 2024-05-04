# Gitleaks protect as pre-commit hook

Check code for sensitive data befor commit.
The actual command.
``` gitleaks protect -v --staged ```

## Installation

- copy _pre-commit_ file to **[your git repo]/.git/hooks** folder
```
cd /your/project/folder
curl -sSfL -o ./git/hooks/pre-commit https://raw.githubusercontent.com/alexanderlukjanenko/gitleaks-pre-commit-hook/main/pre-commit
```
- set exec permissions
``` chmod +x ./git/hooks/pre-commit ```
- try to commit a sensetive data


``` curl -sSfL https://raw.githubusercontent.com/alexanderlukjanenko/gitleaks-pre-commit-hook/main/install.sh | sh ```

