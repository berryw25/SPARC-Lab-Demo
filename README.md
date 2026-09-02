# General README Guidelines
GitHub repositories can be public or private. Usually, a project in progress would be private and a finished project would be public (assuming you want people to be able to access your work for reproducibility purposes and you haven't included this information on OSF or something similar). Therefore, README's can vary heavily depending on what stage the project is in and what function you want a repository to serve. 

For projects in progress, the guidelines around what a README includes is more lab specific. Generally, you should include:
1. An overall project description
2. Descriptions for what each folder or type of document includes
   — This should involve describing naming conventions and any specificity around what order to run scripts in (if that's important)
3. Some kind of way to access the codebook for the project
   — This could include the codebook itself in the README or a link to it
4. Anything about the version of R needed to run the project (potentially along with required packages)
5. Mention of where to access the raw, de-identified data

Finished projects are more specific as to what a README should include. Usually, you can find a list of necessary things to include online. 

======================================================================================================

There are two main ways you can use a GitHub repository - through the GitHub website and the GitHub desktop application. You use these in different ways.
Using it through the website is simpler, but it can lead to more issues, so I'd suggest only using the application when possible. The website version serves as the primary source for the project. The application allows you to make local changes. Git is a version-control system that tracks changes to files. GitHub is built around Git to make collaboration, storage, and project management easier. A repository is a project folder whose history is tracked by Git.

GitHub tab descriptions:
1. Branches are diversions from the original branch of the project. They contain the same information as the main branch, but any commits you make to the new one are isolated in that branch.
2. Issues can generally be used as a brainstorming area. This tab probably won't be particularly useful for us, because we largely work in the same area. It can be useful when collaborating with people from different universities, though.
3. Pull requests primarily concern potential branches. If someone finishes work on a branch and wants the rest of the members in the repository to use it, they can make a pull request.
4. You can manage who has access to private repositories through the settings --> accessibility tab.

GitHub basic terms:
1. Clone - download a GitHub repository onto your computer (downloads it in its current state and will not update if someone pushes a new commit)
2. Commit - a confirmed change you want to make to a file on the project (this will not alter the main repository until you push the commit)
3. Push - send your commits to the main GitHub repository (you must do this at the end of each working block to save your work)
4. Pull - get any changes to the project from GitHub (you must do this before you work on the project to ensure you receive everyone elses changes)
5. Branch - separate version of the project you're working on
6. Pull request - request for others to accept the changes to the project that you've been working on in your separate branch
7. Merge - if people accept the pull request, this merges the actual changes with the main branch

General workflow on GitHub:
Clone --> edit R script or document --> commit changes --> push them to GitHub --> potentially deal with pull requests depending on who is managing the repository

Other important things to know:
1. When making a commit, it will ask you to include a description of what the commit is. Please make sure this description is actually descriptive (it helps others know what you actually did).
2. Be careful with what you're uploading to GitHub. We likely will only be using private repositories, but you still don't want to upload any identifiable data.
3. .gitignore explains what files GitHub will not track (not super important to know how that works)
