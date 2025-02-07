# CISC 365 - Algorithms I 

The following are the test topics:
1. Complexity (Lectures 1-8)
2. Divide-and-Conquer (Lectures 9-14)
3. Greedy Algorithms 
4. Dynamic Programming
5. Branch-and-Bound

## Misc

So, for this repository, I [learned](https://stackoverflow.com/questions/42871542/how-can-i-create-a-git-repository-with-the-default-branch-name-other-than-maste) how to initialize a GitHub repository without using GitHub itself. 

I will create a GitHub repository with a **master** branch of my choice. This can be anything, but for the sake of consistency, I've decided to use ```main```. If we just use ```git init```, before the following command, we cannot change the branch name without deleting the default ```master``` branch.

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



