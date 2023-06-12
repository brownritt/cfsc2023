# Starting a GitHub enabled project

While there are many ways to start a project on your machine that is also GitHub enabled, it is easier to take steps in a specific order.

- Make the repository on GitHub using a web browser
    - Include the default `README.md` file.
    - You may choose to also add a `.gitignore` file (GitHub has templates for many programming contexts) and/or a `LICENSE`.
- Clone the repo to the desired location on your machine, using the instructions in the "Code" button on your repo's webpage. Note: do *not* download a Zip file; you must actually *clone* the repo.
- Add subdirectories for your project skeleton
- Edit the `README.md` to add your project information
- Edit the `.gitignore` to exclude data or figures directories (or anything that will be large files), plus any system dependent files (like `.DS_Store` on Macs).
- Add+Commit your changes locally, push your changes to GitHub
- Copy any other files you need to your project
- Add+Commit. Push.
- Start coding. Add+Commit+Push.

If you return to a project after some downtime, it is a good idea to `git fetch` and then check `git status` before doing anything else. This will make sure your local copy is aware of any changes that may have been made to the remote on GitHub.

The convenience of creating the repo on GitHub first and then cloning it locally is
- The remote URLs are automatically set (check `git remote -v`)
- You can use templates for common files

