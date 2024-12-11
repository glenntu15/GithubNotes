# This is a README markdown file
we will use this for github comments
…or create a new repository on the command line
echo "# GithubNotes" >> README.md
```
git init
git add README.md
git commit -m "first commit"
```
```
git branch -M main
git remote add origin https://github.com/glenntu15/GithubNotes.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/glenntu15/GithubNotes.git
git branch -M main
git push -u origin main

```
…or import code from another repository
## To update the local folder from a repo
...
git pull 
...
or
...
git pull orgin main
...
## How to merge branches in GitHub

1. Navigate to your repository, then find and click the Pull requests button. It should be in between the Issues and Actions buttons. You’ll see a summary of all pull requests you have pending.
2. Navigate to and click on the pull request you’d like to merge into the main branch.
3. Now, you have a few choices for initiating the merge, depending on your repository’s merge options:
   - Merge every commit into your main branch:
     To do this, click Merge pull request. If this button does not appear, open the dropdown menu and click on Create a merge commit.
   - Combine the commits into one large commit:
   You can “squash” your commits together by clicking the dropdown menu, then choosing Squash and merge and clicking the new Squash and merge button. Doing this helps    you create a cleaner, more streamlined Git history for your repository.
   - Rebase each commit onto the main branch:
To do this, click the dropdown menu, choose Rebase and merge, and click the new Rebase and merge button. This also creates a cleaner project history.
4. You can now leave a comment if you’d like, or you can accept the default message GitHub provides you.
5. Scroll below the commit message field to choose a Git author email address.
6. Click on Confirm merge, Confirm squash and merge, or Confirm rebase and merge, depending on which option you choose in Step 3.
7. If the merge occurs successfully, GitHub will display a note stating so. This helps confirm that you’re good to go.
8. If you’d like, you can now delete the branch by clicking Delete branch to keep things nice and neat. Alternatively, you can set it up so that the branch deletes automatically once you complete a merge to save some time.
