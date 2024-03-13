HOW TO CONTRIBUTE TO THE DASHBOARD PROJECT

Step 1. Fork this repo (You can only fork this repo with your computer or mobile device in desktop mode)
fork this repo by clicking the Fork icon in the top right corner of this repo.

Step 2. Clone the repo
Clone this project to your local code editor (VSCode), go to your terminal, navigate to your desired folder, use the following command in your terminal:

git clone https://github.com/<your-github-username>/dashboard
Press enter

cd dashboard
For example,

git clone https://github.com/folarh/dashboard
cd opensource101

Step 3. Add your changes

Step 4. Create a new remote for the upstream repository.
Connect your forked project to this repo

git remote add upstream https://github.com/folarh/dashboard

Step 5. Create your branch
git checkout -b <branch-name>
For example

git checkout -b fola-branch
Ensure no space in between your branch name.

Step 6. Add your changes to git
git add .
Step 7. Commit your changes to git
git commit -m "<add your commit message>"
For example

git commit -m "add my details to the repo"
Step 8. Push your changes to git
git push -u origin <branch-name>
For example

git push -u origin fola-branch
Step 9. Create a pull request.
After pushing changes to your branch, you are ready to send a pull request.

Follow these simple steps.

Go back to your repository (your forked version of this repo) in your browser.
Refresh your page.
You should see a “Compare and Pull Request” button. If you see the button, proceed with Step 4, if you don't see it, proceed with Step 3i.
i - Click the Pull request in your forked repo to navigate to the Pull request tab
