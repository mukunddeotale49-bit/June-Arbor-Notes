# SCM (Source Code Management) 

## What is SCM?
- SCM (Source Code Management) is the practice of tracking and managing changes to software code. 
- It helps developers collaborate, maintain code versions, and ensure consistency across a project.

## Difference Between Centralized VCS and Distributed VCS
- https://www.geeksforgeeks.org/git/centralized-vs-distributed-version-control-which-one-should-we-choose/




| Feature              | Centralized VCS (CVCS) | Distributed VCS (DVCS) |
|---------------------|---------------------|---------------------|
| Repository         | Single central repository | Multiple repositories (local + remote) |
| Example Tools     | SVN, Perforce        | Git, Mercurial      |
| Offline Work      | Not possible        | Possible (local commits) |
| Speed            | Slower (relies on central server) | Faster (local operations) |
| Collaboration     | Requires network access | Can work offline and push later |

![cdcsdvcs](./images/cvcsdvcs.png)

## Git branches 
- https://www.atlassian.com/git/glossary#commands
## Git Branching

Branching in Git allows developers to work on different versions of a repository independently. Branches help manage features, fixes, and releases without affecting the main codebase.

### Common Types of Branches
1. **Main (Master) Branch** - The primary branch where production-ready code is maintained.
2. **Feature Branch** - Used to develop new features before merging into the main branch.
3. **Dev** - Used to store ongoing devlopment code
4. **Test** - Used to test the code in this branch 
5. **Release Branch** - Used for final testing before deploying a new version.
6. **Hotfix Branch** - Used to quickly patch critical issues in production.
![](./images/gitbranch.png)

![](./images/gitbranch1.png)
