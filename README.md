# demo_test1

## To create a repo without README.md

#### To make a directory in download folder:
`mkdir demo_test1`

![alt text](https://user-images.githubusercontent.com/25001852/86913896-f886be00-c13c-11ea-8293-11d987521b2e.png)

#### To create a readme.md file:
`echo "# demo_test1" >> README.md`

#### Initialize the directory:
`git init`

#### Create and add a README.md file:
`git add README.md`

#### Commit the changes:
`git commit -m "first commit"`

#### Add the origin where we have to push the file. This is the SSH Repo link:
`git remote add origin sshrepolinkhere`

#### Push the file:
`git push -u origin master`

![alt text](https://user-images.githubusercontent.com/25001852/86914009-31269780-c13d-11ea-8519-76d4103be861.png)

## To add file to repo

#### To pull the file that is added in the remote repo to local repo, use pull command:
`git pull`

![alt text](https://user-images.githubusercontent.com/25001852/86915095-04737f80-c13f-11ea-944a-2c7cf9f06e8e.png)
![alt text](https://user-images.githubusercontent.com/25001852/86915220-3b499580-c13f-11ea-9ca1-1a520fbd61cc.png)
![alt text](https://user-images.githubusercontent.com/25001852/86915357-7cda4080-c13f-11ea-8550-19deeacc42a9.png)

#### To add a branch in master branch:
`git branch branchname`

#### Switch the branch:
`git checkout branchname`

#### Adding a file in branch:
`echo "#content">> filename.txt`

#### Add the file and push the file. To create the branch remotely we have to use:
`git push --set-upstream origin branchname`

![alt text](https://user-images.githubusercontent.com/25001852/86916988-07bc3a80-c142-11ea-88c3-e395f9cfc9b3.png)

#### Switch the branch again to the master:
`git checkout master`

#### Merge commange to merge the branches:
`git merge mybranch`

#### As the merge command is used the new create branch will be merged to the master branch and the file will be inserted to it. Previously, we have 2 file in the master, now there are 3 files. Make sure to push the files using:
`git push`

![alt text](https://user-images.githubusercontent.com/25001852/86917132-3e925080-c142-11ea-859b-1652369ddd8b.png)
