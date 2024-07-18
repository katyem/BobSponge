# BobSponge

This is a sample CV using the hugo-resume theme. This is intended for educational purposes only! 

**Directories of primary interest:
"static/img"
"content"

**Files of interest
config.toml
netlify.toml

Use a free netlify.com site through your github account.

## Instructions for Github

Use github desktop to upload your file updates (in R) to your github folder.  Netlify will monitor and update your page when it detects an update.Step 1: Install GitHub Desktop

Step 1: Download and install GitHub Desktop from here.

Step 2: Create a GitHub Repository

Open GitHub Desktop.
Click on File in the top menu and select New repository....
In the "Create a New Repository" dialog:
Name your repository BobSponge. (or use your name and change all reference throughout this doc)
Choose the local **path** (not the folder, Github will make a folder with the same name as the repository) where you want the repository to be stored on your computer.
Optionally, add a description.
Ensure the "Initialize this repository with a README" checkbox is checked.
Click Create repository.

Step 3: Set Up Your Markdown Website
Navigate to the local repository folder Github just created.
Copy the files from the BobSponge example.

Step 4: Commit and Push to GitHub
Open GitHub Desktop.
You should see your changes in the Changes tab.
Write a commit message (e.g., "Initial commit with markdown files").
Click Commit to main.
Click Push origin to upload your local repository to GitHub.

## Edit the files

Primary page info is in the "/content/_index.md" file.
Edit the file in your favorite editor (I use R-Studio so I can add R-markdown files to my site)


## Set up Netlify.com account using Github login

Go to ![Netlify.com](https://netlify.com) and sign up or log in.
Click on New site from Git.
Select GitHub as the provider and authenticate if necessary.
Find and select your repository (i.e., BobSponge).
Netlify will automatically detect your build settings. You may need to specify the build command and publish directory if you're using a static site generator (e.g., for Jekyll, it might be jekyll build and _site).
Click Deploy site.

## Change the navigation menu

Go to the folder on your computer from the main project directory (i.e., BobSponge): "\themes\hugo-resume\layouts\partials\nav.html"
Move the "if" statements up or down. Moving Skills block of code below the Education block will change the order in the navigation menu.




![nav.html](nav.html_image.png)

![https://bobsponge.netlify.app](https://bobsponge.netlify.app)
 
Please do not distribute any of the images associated with this project. If you use this as your template for your CV, go to the "static/img" folder and delete all of the images and replace with your own (hint, use the same image names, like qr-code.png, and you don't have to recode).

100% of my students who used this template landed a job!  She was really happy.
