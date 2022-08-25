# README #

 - First branch out from master to your local as feature branch
    - Example: feature/ratha
 - Make a couple of line changes then for each of the following branches:
    - dev
    - staging
    - uat 

    Create a branch off of that with the prefix bridge- 
    example: bridge-feature/ratha

    Then use git cherry-pick using the SHA key created for your commit to select the code from your earlier branch

 - Then use git rebase to merge into the master.

## Example commands for git
- git log
- git cherry-pick {SHA KEY}
    - git cherry-pick --abort
    - git cherry-pick --continue
- git rebase [branch]
    - git rebase --abort
    - git rebase --continue

##### * For the comment please start with ticket number as it is much easy to know what ticket is this comment is for" 
- Example: git commit -m "SV-123: Add main html file"