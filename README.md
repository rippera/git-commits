# Git Conventional Changelog

# Installation

```bash
npm i cz-conventional-changelog --save-dev
yarn add cz-conventional-changelog --dev
```
# Instruction
```bash
git add .
yarn/npm cz and fallow instructions
git push <branch_name>
```

# Config

```bash
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog",
            "disableScopeLowerCase": false,
            "disableSubjectLowerCase": false,
            "maxHeaderWidth": 100,
            "maxLineWidth": 100,
            "defaultType": "",
            "defaultScope": "",
            "defaultSubject": "",
            "defaultBody": "",
            "defaultIssues": "",
            "types": {
              ...
              "feat": {
                "description": "A new feature",
                "title": "Features"
              },
              ...
            }
        }
    }
```
