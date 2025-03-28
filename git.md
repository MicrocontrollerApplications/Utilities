# Git
Git is nowadays probably the most common Version Control System for Software Development. Version Control is mainly used to create a development history 
during development. This reduces the potential of data loss and enables one to easily reset changes. Furthermore, in professional software development teams 
Version Control can be used to review the work of colleagues to improve code quality and reduce the potential for bugs.

Within this lecture we will not actively use Git, but GitHub to provdie you with the relevant code for your laboratory sessions.
Therefore, mainly one feature of Git is necessary - cloning a repository. Those who want to know more about Git, should take a look at the [References](#references)

## Git Clone
If not stated otherwise within the repositories README, cloning a git repository is always the same and requires the below 4 steps.
### 1. Get the repository's link (in our case from GitHub)
---
Links to the relevant repositories are provided via Moodle for each laboratory session. For this example we use the repository for our first lab session https://github.com/MicrocontrollerApplications/Lab1_HelloWorld.

![How to get repository link](git_images/getRepoLink.png)
### 2. Open Git bash
---
<img src="git_images/GitBash.png" alt="Open Git Bash" style="width:75%; height:auto;">

### 3. Clone the repository :)
---
With Git Bash opened, you can use git clone to get the project from GitHub. The command git clone is structured as shown below.

```bash
git clone <repository link> <target directory>
```

In case of the first laboratory session the relevant command would be:

```bash
git clone https://github.com/MicrocontrollerApplications/Lab1_HelloWorld.git U:/Microcontroller/Lab1
```

> [!TIP]
> You can highlight / mark above command, copy it to your clipboard, and paste it into Git Bash using right mouse click -> insert.

> [!WARNING]
> In case you read this manual, in a lab session other than lab 1 - **change the target folders name!!** 

If you want your repository to be stored in a different folder simply change the location from *U:\Microcontroller\Lab1* to you prefered location. But keep in mind that it's harder to support you in case you use a different setup.

## References
1. [Medium - An Introduction to Git for Beginners](https://medium.com/chaya-thilakumara/an-introduction-to-git-for-beginners-c97e701cecf9)
1. [Oh My Git - An open source game about learning Git!](https://ohmygit.org/)
1. [Git Documentation](https://git-scm.com/doc) (This is really for advanced Git users)
