# github-certification

# 1. GIT CONFIG COMMANDS

git config --list --show-origin (File location)
git config --list --show-scope (All types with wording)
git config --list --name-only  

git config --global --replace-all user.name 'JATIN GUPTA'
git config --get user.name (scope Optional)

# List the data
Git config —list
Git config —list —local (Vice versa)
Git config —list —system
Git config —list —global

# Edit the data
Git config —edit
Git config —edit —local
Git config —edit —system
Git config —edit —global

# Filter any value
git config --global --list | grep user.name