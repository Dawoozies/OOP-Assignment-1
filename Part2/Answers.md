# Part 2 Questions:
### Answers

1. Mercurial, GitHub, SourceTree
2. The main advantage is being able to make changes/add to a project and have them integrated into the main project very quickly. 
Also version control, being able to have backups of the project at different stages. Developers can roll back the project to a previous commit
if required. Branching allows developers to prototype new features independent of the main project and if these features work out well then they
can be merged into the main branch.
3. 
Branch: An independent version of the main branch (or other branches) where changes can be made without affecting the origin branch

Pull: Download current version and all changes from the repository to the local repository

Push: Upload local repository and all changes to the main repository

Repository: The currently 
5. VSCode has a merge tool feature where 
6. 

1: <<<<<<< HEAD the main marker which marks the start of the original code

2: ======== marks end of the original code and the start of the new changes to the code replacing it

3: >>>>>>> develop marks the end of the changes

``` csh
        OLD CODE AT LINE 1
        OLD CODE AT LINE 2
    <<<<<<<< HEAD
        OLD CODE AT LINE 3
        OLD CODE AT LINE 4
        OLD CODE AT LINE 5
    =============
        NEW CODE AT LINE 3
        NEW CODE AT LINE 4
        NEW CODE AT LINE 5
    >>>>>>>> develop

```

7. Use a merge tool (like VSCode) to view the merge conflicts. Look at the old code and the new code and choose if you want to keep the new changes or the old changes
8. Git revert makes a new commit that undoes any changes made in a commit
9. Git reset deletes the entire commit from the commit history
10. Revert adds a new commit to which undoes something, Reset deletes the entire commit from the history
11. False: Broken code should not be commited to the main branch, if a developer knows the code is broken but needs to commit for some reason then they should push it to a branch
12. True: If a developer has completed work on some change which is stable then they should commit before beginning a new task, as the newly added code may for one reason or 
another need to be reverted and won't overlap and cause issues with other systems.
13. DevOps: Standing for Development and Operations, is a methodology in software dev to automate and integrate software development teams and IT teams 
14. 

GitHub:

Bamboo (Atlassian):

GitLab: 

15. CI/CD standing for Continuous Integration and Continuous Deployment: CI/CD is a workflow where the process of unit testing, building and releasing software is automated by some tool.
Game CI is an example of a CI/CD system for specifically Unity. When set up, developers can commit their changes to the project and then have those changes be unit tested
on a remote server. When the unit tests are passed the server will build the game and if successful can upload the build to specified platforms (Itch.io, Steam, etc)