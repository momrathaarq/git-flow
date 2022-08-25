# README #

 - First branch out from master to your local as feature branch
    - Example: feature/ratha
 - Making a couple line change then do the cherry pick to following branch with prefix bridg- example: bridg-feature/ratha
    - dev
    - staging
    - uat 
 - Then using git rebase to merge into the master

## Example commands for git
- git cherry-pick ###$$#%#$%
    - git cherry-pick --above
    - git cherry-pick --continue
- git rebase [branch]
    - git rebase --above
    - git rebase --countinue

##### * For the comment please start with ticket number as it is much easy to know what ticket is this comment is for" 
- Example: git commit -m "SV-123: Add main html file"