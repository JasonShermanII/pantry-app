This will be the journel of all learned and covered concepts explored throughout the project. The contents will be the What and Why something was used, and to share my inner thinking along with the project. Most of the contents may just be basic vocabulary or funtions with there given purpose, others may be more abstract further developing the reason behind implimentation.

What is .md (Markdown)?
Markdown (.md) is a lightweight markup language with plain text formatting syntax. It is designed so that it can be converted to HTML and many other formats. It allows developers to format text (bolding, headers, list) using standard keyboard characters rather than relying on heavy graphical word processors (like Microsoft Word)
It is the developer's version of writing a formatted document. Instead of clicking a "Bold" button with your mouse, you just type **this**. Instead of clicking "Header", you type # Header. It allows you to write clean, structured documentation without ever taking your hands off the keyboard. GitHub uses Markdown to display the README.md files on repository front pages.

What does "Untracked" (Green Text on files) mean?
In Git version control, an "untracked" file is a file that exists in the local working directory but is not currently included in the Git index (the staging area) and has no previous history in the repository. Git sees the file exists, but is not monitoring it for changes.

The Git Workflow (add, commit, push)
git add <file> (staging): Moves changes from the working direcotry to the staging area, preparing them to be committed.
git commit -m "message" (committing): Captures a snapshot of the currenlty staged changes and permanetly records them in the local repository's history log. 
git push (pushing): Uplaods local repository content (commits) to a remote repository (like GitHub).

Virtual Environment (venv)
A self contained directory tree that contains a Python installation for a particular version of Python, plus a number of additional packages. It allows developers to manage project specific dependencies in isolation, preventing version conflicts with the global Python environemnt.

Flask Library
A lightweight WSGI (Web Server Gateway Interface) web application framework written in Python. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It handles routing request from URLs to specific Python functions.

Tip for the terminal
When working on the pantry project youll want to run (source venv/bin/activate) to stay inside the sandbox while working on the app. After it is simply (deactivate) to go back to normal terminal. 99% of the terminal is the exact same. The only thing the sandbox changes is that when you type the words python or pip, the terminal intercepts that command and routes it to your venv folder instead of MAC's global system.