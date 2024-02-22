### Concepts
*For this project, we expect you to look at these concepts:*

- [Authenticating Git](https://intranet.alxswe.com/concepts/100035)
- [Struggling with the sandbox? Try this: Using Docker & WSL on your local host](https://intranet.alxswe.com/concepts/100039)
- [Source code management](https://intranet.alxswe.com/concepts/22)
- [Right-engineering, right-documenting](https://intranet.alxswe.com/concepts/6)
- [Git and Github cheat sheet - Everything in less than 30 seconds](https://intranet.alxswe.com/concepts/57)

## Resources  
## Read or watch:
- [Resources to learn Git](https://intranet.alxswe.com/rltoken/fq9RPlPS5IdYzOWTvwbdFQ)
- [About READMEs](https://intranet.alxswe.com/rltoken/R7MeJ8alpK3JoVF8w24wiQ)
- [How to write a Git commit message](https://intranet.alxswe.com/rltoken/FYsjjR-97Hk4NJtgqzWdtQ)

**Resources for advanced tasks** (Read only after finishing the mandatory tasks):
- [Learning branching](https://intranet.alxswe.com/rltoken/tN8ZJ0yWubOP6jdciqtrFw)
- [Effective pull requests and other good practices for teams using GitHub](https://intranet.alxswe.com/rltoken/mjpQ9OCU0Dz-DFxZjASEJg)

## Learning Objectives  
At the end of this project, you are expected to be able to [explain to anyone](https://intranet.alxswe.com/rltoken/jj0uPL9hiKF10KCH4u620A), **without the help of Google:**

## General
- What is source code management
- What is Git
- What is GitHub
- What is the difference between Git and GitHub
- How to create a repository
- What is a README
- How to write good READMEs
- How to commit
- How to write helpful commit messages
- How to push code
- How to pull updates
- How to create a branch
- How to merge branches
- How to work as collaborators on a project
- Which files should and which files should not appear in your repo

## Requirements  
## General
- A `README.md` file at the root of the `alx-zero_day` repo, containing a description of the repository
- A `README.md` file, at the root of the folder of this project (i.e. `0x03-git`), describing what this project is about
- **Do not use GitHub’s web UI**, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
- Your answer files should only contain the command, and nothing else

## More Info  
## Basic usage
At the end of this project you should be able to reproduce and understand these command lines:

```shell
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
```

### Quiz questions

## Question #0

You have the following files in your project directory:

```
julien@ubuntu:/tmp/git_project$ ls
0-test  0-test~ #0-test# file1  file2
```

You’ve edited `0-test` and you want to add it to your GitHub repo. What is the correct command to add **only** `0-test`?

- [ ] git add .

- [ ] git add -N 0-test

- [ ] git add 0-test

Tips:
You should learn what each of these commands would actually do if you were to execute them!

## Question #1

What command can you use to see what changes have been staged, which haven’t, and which files aren’t being tracked by Git?

- [ ] git init

- [ ] git status

- [ ] git checkout
