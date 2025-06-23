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


