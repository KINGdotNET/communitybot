CHANGE MANAGEMENT
  
add git remote address 
git remote add upstream https://github.com/otherAuthor/projectname.git

To verify the new upstream. 
git remote -v 
origin https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch) 
origin https://github.com/YOUR_USERNAME/YOUR_FORK.git (push) 
upstream https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git (fetch) 
upstream https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git (push)

update from upstream to local PC then upload to github clone/fork. 
In terminal run, 
git fetch upstream // fetch from upstream master 
git checkout master // check out local fork master 
git merge upstream/master // merge changes from upstream/master to local master branch. 
git push // to push to github clone
 
git remote set-url --add origin url_address // add origin
git remote set-url --delete origin url_address // delete origin

Let's update.
git add . 
or
git add filename
git commit -m "comment message"
git status
git push
