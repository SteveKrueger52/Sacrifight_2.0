# Sacrifight_2.0
Re-Make of our Global Game Jam game from 2016
___
####Format:
The top-level of this repository is for files that are not part of the Unity project.

The Unity project folder is called Sacrifight_Unity.  
When opening this project in Unity for the first time, highlight this folder and open the project from there.
___
####TODO:
The TODO.md file describes what parts of the project various people are working on.

Commits to **master** that change only the TODO file are completely fine.  
Items have a checkbox to denote whether they are done or not, and several flags that denote various things:
- `CRITICAL` things should be prioritized.
- `IN PROGRESS` things are in progress in the specified branch.
- `BLOCKED` things are blocked by the specified feature, meaning they cannot proceed until that feature is done.

Items with no flags are assumed to have not been started.  
For a reference on how to use the .md format for GitHub, visit [this guide.](https://help.github.com/categories/writing-on-github/)
___
####Git Ettiquette: 
The **master** branch should always work.  
Any features that do not work should not be pushed to **master** until they do.
 
When pushing a new feature from your branch to **master**:
- First pull **master** to your branch
- Make sure your code still works in the **master** environment
- Then merge your branch to **master**

Commit details and names are not necessary on local branch commits, though you may want them for yourself.  
Commits (and merges) to **master** should always include some sort of changelog describing what features were added.
  ___
####Code Ettiquette: 
In the **master** branch, code should preferably be easy to read and documented.  
In other branches, anything goes, but code should be documented before merging with **master**.
