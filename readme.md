Create New Repo on GitHub
-- went to GitHub and created new account via button located next to my profile picture.
-- named it basic_repo and gave a description.

Create Local Repo
-- mkdir basic_repo
-- git init
-- git remote add origin https://github.com/Ballycyrk/basic_repo.git

Create some files inside local repo & add content
-- touch index.html
-- touch style.css
<<added content>>

Add, commit and push these changes to GitHub
-- git add .
-- git commit -m "Original Commit"
-- git push -u origin master

Make more changes to Local content & push to Github
-- subl ../basic_repo/
<<added more changes>>
-- git status
-- git commit -am "add content and styling"
-- git push origin master
