# Repo auto updater
This project can be set up to automatically run a git pull for a custom list of repos on startup.
Steps:
1. Open Update-GitRepositories.psm1
2. Edit `$GitFolders` to include the repos to be updated automatically.
3. Copy the `Update-GitRepositories` folder to `C:\Program Files\PowerShell\7\Modules`.
4. Copy `repo_auto_updater.cmd` to `...\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`.