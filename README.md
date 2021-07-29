https://youtu.be/govmXpDGLpo

git checkout <branch>
git tag <tagname> // create lightweight tag at current branch commit
git tag -a <tagname> -m "<comment>" // create annotated tag, stored as a git tagger object with all information

git tag // to list tags
git show <tagname> // show detailed tag info
git tag -l "v*" // wildcard

git push origin <tagname> // push  tag to GitHub with commit, even if master is not updated yet
git push origin --tags
git push --tags

git tag -d <tagname> // delete a tag
git push origin -d <tagname> // remove a tag from remote
git tag -d <tagname> <tagname> ... // delete multiple tags
git push origin -d <tagname> <tagname> ... // remove multiple tags from remote

git checkout -b <branch> <tagname> // create a new branch base of tag
