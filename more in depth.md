
# The initiating commands;

## `git init [project-name]`
> Used to __initiate a new project__.
- This command is not usually used as people will create them on some version control service(Eg. GitHub). 
- `clone _URL_` will usually be your starting point.

## `git clone [url]`
> Used to __clone a remote repository__ through the `url` 
- This command can be used to clone(copy) the repository(projects) from sources on the version control service.
- Try to clone this project by running `git clone https://github.com/lowzhao/learningGit.git`.
- Always put your username in the link. Eg. `https://[username]@github.com/lowzhao/learningGit.git` This will prevent git from asking you to type the password.

# The configuration commands;
#### These code are usually run once.
## `git config --global user.name [username]`
## `git config --global user.email [email]`
> Used to __setup user info__
- This command usually run once and your computer will know your username and email, and try to do use the username when commiting or pulling from remote repo.

## `git config --global color.ui auto`
> Used to __makes _unicorn___
- Just kidding it's used to make your command line interface colorful.

# The pushing commands;

## `git status`
> Used to __get status of commits__
- To know what you have added and commited on your git repo.

## `git diff`
> Show __differences you haven't commit__
- To see what changes you made that haven't added and commited
- You will get into a situation where you cannot move your cursor or press anything other than `j` and `k` type `wq` to quit.


