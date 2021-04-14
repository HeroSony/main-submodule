### Main Module

## How to add submodule into main module

- Create a new submodule repo
- In main module root directory, git submodule add [submodule-repo-link]
- git add . && git commit -m "Add submodule" && git push origin main
- This will push a new submodule to main module repo but not push any contents inside submodule folder.
- Cd into submodule folder, change somethings and git push
- This will update only module that we have updated.
