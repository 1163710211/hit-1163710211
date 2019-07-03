#How to contribute my source code
This document describes the composition and operation of the ThinkPHP team, what benefits your submitted code will bring to the ThinkPHP project, and how we can join us.
Contributing code via Github
ThinkPHP currently uses Git to control the version of the program. If you want to contribute source code to ThinkPHP, first get an idea of ​​how to use Git. We currently host the project on GitHub, and any GitHub user can contribute code to us.

The way to participate is very simple, fork a ThinkPHP code into your warehouse, modify it and submit it, and send us a pull request, we will review the code and process your application in time. After the review, your code will be merged into our repository, so you will automatically appear on the contributor list, very convenient.

We hope that the code you contributed will be:
+ThinkPHP coding specification
+Appropriate comments that others can read
+Follow the Apache2 open source protocol

#GitHub Issue
GitHub provides the Issue feature, which can be used to:
+Raise a bug
+Proposed functional improvement
+Feedback experience
This feature should not be used for:
+Suggestions for revision (involving code signature and revision traceability issues)
+Unfriendly speech

#Quick modification
GitHub provides the ability to quickly edit files
1.Log in to your GitHub account;
2.Browse the project file and find the file to be modified;
3.Click the pencil icon in the upper right corner to modify it;
4.Fill in Commit changes related content (Title is required);
5.Submit your changes and wait for CI verification and administrator merge.
If you need to submit a large number of edits at once, please continue reading the following

#Complete process
+Fork this project;
+Clone your fork project locally;
+Create a new branch and checkout the new branch;
+Add this project to your local git repository as an upstream (upstream);
+Make changes. If your changes include additions or subtractions of methods or functions, please remember to modify the unit test file;
+Rebase (rebase) your branch to the upstream master branch;
+Push your local repository to GitHub;
+Submit a pull request;
+Wait for CI verification (if you don't pass, repeat 5~7, GitHub will automatically update your pull request);
+Wait for the administrator to handle and rebase your branch to the upstream master branch (if the upstream master branch has modifications).
If necessary, you can git push -f to force the rebase branch to its own fork
Never use git push -f to force push changes to the upstream

#Precautions
+If you have any questions about the above process, please check out the GIT tutorial, such as this;
+For changes to different aspects of the code, create different branches in your own fork project (for reasons see section 9 of the full process);
+For rebase and interactive rebase operations, see Git Interactive Rebase

#Development environment
+jdk：1.7/1.8 
+eclipse 
+tomcat7.0
+MySQL5.7