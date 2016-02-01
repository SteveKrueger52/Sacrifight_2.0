# Sacrifight_2.0
Re-Make of our Global Game Jam game from 2016


Format: 
  The top-level of this repository is for files that are not part of the Unity project.
  
  The Unity project folder is called Sacrifight_Unity.
    when opening this project in Unity for the first time, highlight this folder and open the project from there.
    
  The TODO text file describes what parts of the project various people are working on.
  commits to **master** that change only the TODO file are completely fine.
    - TODO things have not been started. Any item without a flag is assumed to be TODO.
    - IN PROGRESS things are IN PROGRESS in a separate branch, and should denote which branch the feature(s) are being worked on.
    - BLOCKED things are BLOCKED by another feature, meaning they cannot proceed until that feature is done.
    - DONE things are DONE


Git Ettiquette: 
  The **master** branch should always work. 
  Any features that do not work should not be pushed to **master** until they do.
  
  When pushing a new feature from your branch to **master**:
    - First pull **master** to your branch
    - Make sure your code still works in the **master** environment
    - Then merge your branch to **master**.
    
  Commit details and names are not necessary on local branch commits, though you may want them for yourself.
  Commits (and merges) to **master** should always include some sort of changelog describing what features were added.
  
  
Code Ettiquette: 
  In the **master** branch, code should preferably be easy to read and documented. 
  In other branches, anything goes, but code should be documented before merging with Master.
