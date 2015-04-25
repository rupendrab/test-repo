# test-repo

## Test Repository to test git and github interactions
```
cd ~/Documents/Coursera
mkdir test-repo
cd test-repo
git init
git remote add origin https://github.com/rupendrab/test-repo.git
git fetch origin
git pull origin master
## Now you have the files in the local directory
```

## Working in the local repository

```
git status
# Add a new file
echo 'My Project' > SomeFile
git status

# Add somefile to staging area (tracked)
git add SomeFile

# Add another file
touch CONTRIBUTING.md
git status

# Now modify the README.md file
git status

# Now add these two files
git add README.md
git add CONTRIBUTING.md
git status

# Modify the README.md again
git status

# Now commit the changes
git commit -a -m "Addition of commit and push to README.md"
git status

# Now push the changes to github
git push origin master

```
