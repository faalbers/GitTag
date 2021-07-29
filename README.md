https://youtu.be/govmXpDGLpo

git checkout <branch>
git tag <tagname> // create lightweight tag at current branch commit
git tag -a <tagname> -m "<comment>" // create annotated tag, stored as a git tagger object with all information

git tag // to list tags
git show <tagname> // show detailed tag info
git tag -l "v*" // wildcard

git push origin <tagname> // push  tag to GitHub with commit, even if master is not updated yet

