# Mini-Project-Basic-Git-Commands 

## Hands-On Git Project: Collaborative Website Development with Git and GitHub 

In this mini project we will create a step by step projectt to simulate work flow of Tom and Jerryusing Git and GitHub. The hands on project will include installation of Git, setting up a GitHub repository, cloning the repository, creating branches, making changes, and merging those changes back into the main branch. 

**Part 1: SetUp and Initial Configuration** 

1. **Install Git:** 


- Visit the [Official Git Website](https://git-scm.com/) and [Download](https://git-scm.com/downloads) the version of Git for your operating sysyem. Follow the installation instructions. 

2. **Create a GitHub Repository:** 


- Signup or login to [GitHub](https://github.com/). 

- My GitHub account page before creating a new repo. 

![GitHub Page](./img/01.%20GitHub%20Before%20Creating%20Repo.png)

- Click the "+" icon in the top-right corner and select "New Repository" 

![Create a GitHub Repo](./img/02.%20Create%20a%20GitHub%20Repo.png) 

- Name your repository (e.g., "mini-project, ai-startup-website") and initialize it with a README file. 

![Name Repository](./img/03.%20Name%20Repository.png)

- Click "Create repository" 

![Create Repository](./img/04.%20Create%20Repository.png) 


3. **Clone the repository:** 


- On your repository's page on GitHub, click the "Code" button and copy the HTTPS URL. 

![Copy Url](./img/05.%20Clone%20Repository.png) 

- Open your terminal or command prompt 

- Create a folder named **git-project** in the folder where you are storing all **DAREY.IO** related work. For example in the Desktop folder on your laptop, you may create a folder called **"darey training"**.

- Change directory into the **"git-project"**  

- Clone (Download) the repositoryfrom GitHub using    

![Pste Url Copy From GitHub](./img/06.%20Paste%20Url%20Copy%20From%20GitHub.png) 

![Cloning (Downloading) Repo](./img/07.%20Cloning(Downloading)%20Repo.png) 

- Since you just clonned your repository, your branch is "main". 

- Navigate into the repository that is clonned. 

![Navigate into the Clonned Repo](./img/08.%20Navigate%20into%20Clonned%20Repo.png) 

- Create an empty file **"index.html"** 

![Createa an Empty File index.html](./img/09%20Create%20an%20Empty%20index.html.png) 

- Add content to the empty file.

![Adding Content](./img/10.%20Adding%20Content.png) 

![Content Added](./img/11.%20Content%20Added.png) 

- Check changes has not been staged. 

![Check Changes](./img/12.%20Check%20Changes.png) 

- Stage changes to the empty index.html 

![Stage Changes](./img/13.%20Stage%20Changes.png) 

![Confirm Changes](./img/14.%20Confirm%20Changes.png) 

Now, after stagging the changes, the file name will appear in **green** in the terminal output. This colour change signifies that the file has been successfully stages, making it ready for the next step, which is committing these changes to the project's history.


-  Confirm changes have been staged for the commit. 

![Commit Changes](./img/15.%20Commit%20Changes.png) 

- This takes the staged changes and records them in the repository's history with a message describing what was done. The commit is a milestone, making a specific point in the project's development. 

- Push main branch to GitHub.

![Push Main](./img/16.%20Push%20Main%20Branch.png) 

This send commits from the main branch on your laptop to GitHub (Remote Repository). 

- Finally the GitHub home page looks like this.

![GitHub After Push](./img/17.%20GitHub%20After%20Push.png)


**Part 2: Simulating Tom and Jerry's Work**: 

To simulate both Tom and Jerry working on the same laptop, you will switch between two branches making changes as each characters. 

1. Tom's Work: 

- Navigate to the project directory you just cloned. 

![Tom Navigate To Project](./img/18.%20Tom%20Navigate%20to%20Project.png) 

This moves you into the folder containing the cloned GitHub repository on your local machine. It is like steppinng into the project's workspace. 

- Check the current branch: This shows you a list of all branches in your local repository. Initially, you will see only the "**main**" branch because that's the default starting point and no other branches have been created yet. 

![Check Current Branch](./img/19.%20Check%20Current%20Branch.png) 

- Create a new branch for Tom's work: 

![Tom's Branch](./img/20.%20Tom's%20Branch.png) 

This creates a new branch named **"update-navigation"** (You can name it whatever you wan). The command also automatically switches to the newly created branch from the **"main"** branch. This branch **"update-navigation"** is where Tom's updates to the website without affecting whatever is in the **"main"** branch. 

- Check the branch again to see your newly created branch. 

![Check New Branch](./img/21.%20Check%20New%20Branch.png) 

Running **git branch** again now shows newly created branch, indicating you're now working in this new **"workspace"** dedicated to Tom's navigation updates. 

- Recall you created an empty file "index.html" in the main and content was added. The  file will also exist in the 'update-navigation-branch': Open the 'index.html' and add the content below. 

![To Add Content](./img/22.%20To%20Add%20Content.png)

![Content Added](./img/23.%20Content%20Added.png) 

This simulates Tom's contribution to the project. This text represents the work he's doing on the navigation bar. In the real world, this will be an actual software code. 

- Check changes has not been staged. 

![Check Change](./img/24.%20Check%20Changes.png) 

At this stage, Tom has modified the file, but these changes have not not been prepared for a commit in Git. This is indicated by the file name appearing in **red** in the terminal output, signaling that the changes are recognised by Git but not yet staged. 

- Staged Tom's changes: git add index.html can be used to stage only index.html file, to staged all the changes in the project for Tom's git add . will be ok.

![](./img/25.%20Stage%20Tom's%20Changes.png) 

This tells Git that you want to include the updates made to **index.html** in the next commit. It is like saying, "Okay, I'm happy with these changes and ready to record them". 

- Confirm changes have been staged for commit: 

![Confirm Changes](./img/26.%20Confirm%20Changes.png) 

Now, after staging the changes, the file name will change or appear in **green** in the terminal output. This colour changes signifies that the file has been successfully staged, making it ready for the next step, which is committing these changes to the project's history. 

- Commit Tom's changes 

![Tom's Commit](./img/27.%20Tom's%20Commit.png) 

This takes the staged changes and records them in the reepository's history with a message describing what was done. This commit is a milestone, making a specific point in the project's development. 

- Push Tom's branch to GitHub: 

![Tom's Push](./img/28.%20Tom's%20Push.png) 

![GitHub Page After Push](./img/29.%20GitHub%20Page%20After%20Push.png)


This send Tom's commits from your local branch on your laptop to GitHub (Remote Repository). It's like publishing your work so that others (or in this case "Jerry") can see and interact with it. This step updates the remote repo with Tom's contributions. 

After complete Tom's workflow you will now simulateJerry's contribution to the project. Todo this you will 

- switch back to main branch, 

- create a new branch for Jerry, 

- make changes, and then 

- Stage, commit, and push this to GitHub. 


1. Jerry's Work: 

- Switch Back to the Main Branch:

![Switch To Main](./img/30.%20Switch%20To%20Main.png) 

This command switches your current working directory back to the main branch, ensuring that Jerry's changes start from the latest version of the project. 

- Pull the latest changes: 

![Pull Latest](./img/31.%20Pull%20Latest.png) 

This ensures that you have the latest changes updates from the
repository, including Tom's merged changes, if any.

- Create a New branch for Jerry's work: 

![Jerry's Branch](./img/32.%20Jerry's%20%20Branch.png) 

This creates a new branch where Jerry will make his changes, keeping them separate from the **main** project until they are ready to be merged. 

-Open **index.html** file by adding contact information. This simulates Jerry's task. 

- Stage Jerry's Work: Before changing contact info was added.

![Jerry's Stage](./img/33.%20Jerry's%20Stage.png) 

This commands stages the changes Jerry made to the **index.html** and everything in the project file, preparing them for commit. 

- Commit Jerry's Changes: 

![Jerry's Commit](./img/34.%20Jerry%20Commit.png) 
![Continue](./img/35.%20Continue.png)

This saves Jerry's changes in the branch's history, with a message describing what was done. 

- Push Jerry's Branch to GitHub: 

![Jerry's Push](./img/36.%20Jerry%20Push.png) 

All the commands use above uploads Jerrys branch to the GitHub repository, making it available for review and merging into the main project.

After the push the GitHub home page looks like this 

![After Push](./img/37.%20After%20Push.png) 


So far you have experienced collaboration between Tom and Jerry , But that is not all. Someone needs to review their work, merge the changes to the main project and resolve conflicts if any. In the next project we will see how that works.