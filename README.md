# CISC 365 - Algorithms I 

The following are the test topics:
1. Complexity (Lectures 1-8)
2. Divide-and-Conquer (Lectures 9-14)
3. Greedy Algorithms 
4. Dynamic Programming
5. Branch-and-Bound

## Misc

So, for this repository, I [learned](https://stackoverflow.com/questions/42871542/how-can-i-create-a-git-repository-with-the-default-branch-name-other-than-maste) how to initialize a GitHub repository without using GitHub itself. 

I will create a GitHub repository with a **master** branch of my choice. This can be anything, but for the sake of consistency, I've decided to use ```main```.

Either command will suffice:

```bash
git init --initial-branch=main
```
```bash
git init -b main
```

If we are using an older version of GitHub, we use the following commands:

```bash
git init
git checkout -b main
```

If we just use ```git init```, before the following command, we can change the branch name using the following command:

```bash
git branch -m main
```

Now we need to create a GitHub repository. We are going to name this ```365-material```. We need to take our link generated, and use the following command:

```bash
git remote add origin https://github.com/mosarhat/365-material.git
```

From here, we need to push using the following command. From this command onwards, we can omit the ```-u```. ```--set-upstream``` is equivalent to ```-u```. The following are two types of commands we can use:

```bash
git push --set-upstream origin main
```

```bash
git push -u origin main
```

To remove a changed file (name or removed), we can use the following commands.

1. First we must check if the file is still being tracked. The removed file should show up in red.

```bash
git status
```

2. *Stage* the deletion of the file.

```bash
git rm README..md
```

If the file is untracked, i.e. does not show up with ```git status```, just remove it from the directory manually.