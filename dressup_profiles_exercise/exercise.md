## Exercise: Add particpant profile to the DResSUP website

* The Task: DResSUP participants will add their own profiles to the [DResSUP website](http://dressup.library.ucla.edu/participants/). 
* The Goal: Introduce participants to Git, GitHub, and Jekyll (a static site generator).

Notes:
* We will be doing "pair programming," meaning two people will work together on a single computer - Macs only today!

#### Getting your own copy of the DResSUP website

First, you'll need to get your own local copy of the website so that you can edit and preview your work:

1. Login to GitHub (https://github.com) 
2. Navigate to the DResSUP website repository (https://github.com/dressupucla/dressupucla.github.io)
3. Fork the repository
  * In the top right corner, there is a **Fork** button - just click it
  * "Forking" copies the repository from one account to another (in this case, from the DResSUP account into your own account). You should see an animation that the repo is being copied
  * Let's explore the repo a bit... (files and file structure, Settings and GitHub Pages, viewing the live site)
  
#### Cloning your repo to your local machine

Next, we'll need to clone our forked repo to our local machines:

1. Open Terminal
2. Change your working directory to the Desktop using the `cd` command, for example `cd Desktop`
3. Clone the forked repo to your Desktop: `git clone [the repo URL]`
4. Change your directory so you are in the newly cloned directory using the `cd` command
5. Now you can verify that you are in the cloned repo directory by using the command `pwd`
6. Let's start the Jekyll server so we can preview the using this command: `bundle exec jekyll serve`
7. Now you should be able to view the website in your browser at http://localhost:4000

#### Add your own profiles to the site

1. Look at the files in the newly cloned `dressupucla.github.io` folder
2. Navigate to the Participants folder
3. Open the _participant_template.md file with Atom or a text editor and copy the template
4. Create a new .md file with your first and last name and paste the template inside
5. For the picture field, type the title of your image file exactly as it is without the file type (ie: .jpg, .png)
6. Save your file.
7. Navigate to the image folder
8. Drop your image file into this folder - make sure that the name of the file is identical to the picture field of your profile.

#### Save and push your changes to your remote repo on GitHub
1. Go back to your Terminal
2. First we stage the changes we made using the `git add .` command. (The `.` means that we will stage changes to all the edited files)
3. After stagins, we commit our changes to the repo (kind of like saving) using the command `git commit -m "add a commit message here"`
4. Now you can push your changes with this command: `git push` - this will push your edits to your remote repo on GitHub
5. Enter your username and password for your github account

#### Merge your changes into the main DResSUP site
1. Let's go back to GitHub and view our fork of the DResSUP website repo - you should see the changes you made to the files here. You can view the commit history and see a record of your edits
2. To send your changes to the main DResSUP site, you need to submit a Pull Request. To do this, click on the Pull Request tab, then click on the big green "New Pull Request" button.
3. The "base" should be set to the DResSUP main repo and the "head" should be set to your fork of the repo.
4. If you have changes to submit, you should see a big green "Create Pull Request" button - click it!
5. Give your pull request a title (and a description if you like), then click on the green "Create Pull Request" button under the description text box.
6. That's it! The DResSUP admins will see your pull request and merge your changes in if everything look A-OK.

