# Learning Git in depth.

Git (/ɡɪt/) is a version control system for tracking changes in computer files and coordinating work on those files among multiple people. It is primarily used for source code management in software developmentbut it can be used to keep track of changes in any set of files. As a distributed revision control system it is aimed at speed data integrity, and support for distributed, non-linear workflows.

### Requirements: 
__Download: [git](https://git-scm.com/)__ 

As cool as it seems, learning git for beginner can be as simple as possible. But for you to advance all the commands available in git, you will require alot of effort to master it.

If you never used command line interface before(... and didn't plan to learn anyways...) [Git Hub Desktop](https://desktop.github.com/) will be your best companion. And this [Git Cheat Sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf), can also be really useful.

Let's start simple.

So every command will start with `git *` something.
`*` will be the thing that we are discussing.
`[]` this will be the part where variable will be placed in, the words inside it will define what to put into.

# The initiation command;

## `git init [project-name]`
> This command __initiate a new project__.
- This command is not usually used as people will create them on some version control service(Eg. GitHub). 
- `clone _URL_` will usually be your starting point.

## `git clone [url]`
> Used to __clone a remote repository__ through the `url` 
- This command can be used to clone(copy) the repository(projects) from sources on the version control service.
- Try to clone this project by running `git clone https://github.com/lowzhao/learningGit.git`.
- Always put your username in the link. Eg. `https://[username]@github.com/lowzhao/learningGit.git` This will prevent git from asking you to type the password.

# The configuration command;

## `git `
