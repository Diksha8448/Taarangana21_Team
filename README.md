# Taarangana21_Team
GIT Commands
For First time using this repo --
	(Hope everyone has installed git on your desktop)
Open command line on your desktop and then go to the desired directory where you want to add this repository.

git clone https://github.com/tanyagarg2509/Taarangana21_Team
cd Taarangana21_Team
Do your changes on your desktop folder
git status ---------- to check on which branch you are, it will show on branch master
git checkout -b “YOUR BRANCH NAME”
It will show on new branch created and branch name that you have mentioned , Use your full name for the branch name
Example -- git checkout -b “TANYA_GARG”
git status { this step is to cross check what changes you have made}
git add -A
git commit -m “message”
git push origin <branchname>
Example -- git push origin TANYA_GARG
Check on github repository whether your branch is successfully created or not.

If already created a branch using the above steps.
git status
If branch name is your branch then okay else use 
git checkout branch_name
Example -- git checkout TANYA_GARG
Do your changes and add them to your branch using (git add, commit,push commands mentioned above)

If in case master branch is updated with some changes and you need to do changes to the latest master’s code and then add it to your branch.
git checkout master
git pull origin master
git checkout <your branch name>
git merge master
This command may result in error -- like Conflicts in some file .. merge aborted , then google the error , if still not resolved ask on group.
Then do your changes and add them to your branch using (git add, commit,push commands)


To fetch someone else’s branch (example, you want the code which Some other person have pushed in her branch & then work on that code in your branch):
git status (check on which branch you are present)
NOTE: Fetching means bringing the repository from remote github to your local desktop for the first time and then use pull commands after fetching 

If fetching someone else’s branch for the first time then use, 
git fetch origin othersbranchname
git checkout yourbranchname
git  merge othersbranchname
	If already fetched someone else’s branch then 
git checkout othersbranchname
git pull origin othersbranchname
git checkout yourbranchname
git merge othersbranchname

In any case there is conflict or some error post it on whatsapp🤣


