# Version Control with Git - EPAM Stage 0 Training

This repository contains all hands-on practical exercises from the **EPAM Stage 0 course "Version Control with Git"**.  
The exercises cover the following topics:

- Basic Git workflow: initializing repositories, adding files, committing changes
- Working with branches: creating, merging, rebasing
- Conflict resolution in merges
- Using tags
- Remote repository management: pushing, pulling, and switching remotes
- Using `.gitignore` to ignore files and directories
- Command-line-only Git operations

## Practical Exercises

### Stage 0 Exercises

1. **I Can Win**
   - Created `song.txt` with the first half of lyrics
   - Committed and pushed changes to GitHub
   - Added the second half of lyrics via GitHub interface and pulled changes locally

2. **Bring It On**
   - Added `.gitignore` to hide `.db`, `.log` files and `target`, `bin` directories
   - Created a feature branch, added commits, merged into master
   - Resolved conflict in `arrows.txt` keeping all lines

3. **Hurt Me Plenty**
   - Created a `storm` branch, added commits to `storm.txt`
   - Added `pursuit.txt` to master and committed
   - Tagged the commit `session1` and rebased `storm` branch

4. **Command-Line Mastery**
   - Pushed the repository to GitHub
   - Created a second GitHub repository
   - Switched remote, pushed all commits, and verified repository integrity
   - Restored original remote configuration
   - All operations performed **entirely via MINGW64 command line**, without GUI tools

## Notes

- This repository is publicly available for learning and demonstration purposes.
- All exercises follow the instructions from the EPAM Stage 0 Git course.
- Commands used include: `git init`, `git add`, `git commit`, `git branch`, `git merge`, `git rebase`, `git tag`, `git push`, `git
