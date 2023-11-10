# How To Collab

#### A small Github Repository based around how to collab on the DragonNetwork Development Team



## Contents
- How to manage Repositories
- How to handle Pull Requests
- When to merge, who to add
- Where to push updates
- How to handle features
- How to actively develop as a team

### Note
- In case you have any better ways feel free to add them and make a Pull Request


## Quick Links
- [How to Manage Repositories](#how-to-manage-repositories)
- [How to handle Pull Requests](#how-to-handle-pull-requests)
- [When to merge and who to add](#when-to-merge-and-who-to-add)
- [Where to push updates](#where-to-push-updates)
- [How to handle features](#how-to-handle-features)
- [How to actively develop as a Team](#how-to-actively-develop-as-a-team)



# How to Manage Repositories
- In general there will be a simple way we manage our repositories, for more info on how to create repositories, branches, commit and pull code it is adviced to look up a guide for your desired software
- The general structure of each repository will include 2 Branches `main` / `master` (or any other name declared as the main branch) and a `dev` (development) branch, we do **NOT** directly push to `dev` or `main`, every new major release of any given project will merge `dev` into `main` as a whole.

# How to handle Pull Requests
- Whenever a Developer issues a Pull request it is important to do a quick Code Review for it, this can be done via the Github Web Interface directly on the Proojects Repository
- Usually not every Developer is involved with every pull request (for example some are for Backend dev and others for Plugin / Web dev), if this is the case, make sure to add Labels, Reviewers and other related data to the pull request.
- Make sure to add a brief description of what your feature does on the Pull Request

# When to merge and who to add
- When you as a Developer are done with your feature, you can start a Pull Request from your branch into the `dev` branch, refer to the **How to handle Pull Requests** section to find out what to add to a pull request
- Make sure to add every person related to the Repositories Project to the Pull Request

# Where to push updates
- As mentioned in **How to Manage Repositories** we do not directly push to `dev` or `main` branches.
- Instead we only push directly to our current Features branch, this will avoid future merge conflicts and other issues related to working as team

# How to handle Features
- Whenever you want to contribute to a Project by adding a feature or anything related to it, you must create a branch
- The branch you created must inherit from the `dev` branch of the repository
- The name of the branch that you created must be a name for your feature (example: get-player-command)
- You can fully modify the branch and push changes to it whenever you need to
- Once you're done, make a pull request from your branch to `dev`, see **When to merge and who to add** and **How to handle Pull Requests**

# How to actively develop as a Team
- Once you know all the techniques we use as a Team you can now proceed to find out how you can actively develop features.
- Whenever you want to work on your feature (that in best case you have your own branch for), you must **always** pull the latest changes from the Projects `dev` branch to stay up to date with the rest of the code
- Always make sure to communicate with the Team, this way 2 people won't work on the same feature
- Do **NOT** merge branches without approval from at least 1 assigned Reviewer (if the repository belongs fully to you, you don't always need approval)
- You will **ALWAYS** need at least 1 Reviewer for your merge in case the Project is related to the entire Development Team (example: main libraries, backend libraries and general Team based APIs)