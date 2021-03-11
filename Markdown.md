> Markdown GIT flow chart. <

> Questions <
 --- What's Markdown? ---
 --- Where is use it? ---
 --- Which are the keywords more useful in markdown? ---

 ---
#MARKDOWN#
 ---

 ![github logo](https://www.pngitem.com/pimgs/m/128-1280162_github-logo-png-cat-transparent-png.png) 


 ----

 > Markdown flow <

 ![github flow](https://nellmedina.github.io/assets/img/github-auto-ssh.png)

 ---

> #Markdown flow steps# <

-> The 1 Step is create a new repository, when we create a repository, we need to choose this options.
		-> Create a README.md
		-> Choose a License (In this case we're going to choose: MIT.License)

---

![github](https://www.softwarelab.it/wp-content/uploads/2018/10/newrepo.png)

----

![github first step example](https://guides.github.com/activities/hello-world/create-new-repo.png)

---

-> The 2 Step is clone the URL HTTPS and paste in the terminal with this command > git clone [URL] (obviously without -> [] <- ) <

![github second step example](https://desarrolloweb.com/archivoimg/general/4494.png)


---

-> The 3 Step is create a new branch in the terminal with this name [-> SPRINT-02 <-]. Inside this branch, we need to create a new branch with the name of (example name) [ -> 01-Example <- ] 

> Commands. <

> ( -> git branch 01-Example <- )
			or
( -> git checkout -b 01-Example <- ) <

![github third step example](https://storage.googleapis.com/cdn.thenewstack.io/media/2018/05/c057fff7-screen-shot-2018-05-17-at-4.18.10-pm.png)


---

-> The 4 Step is check the Status with this command.
> git status <

![github four step example](https://miro.medium.com/max/1668/1*zLxE3Deuc2ePubedcXvlnQ.png)


---

-> The 5 Step is open the Code Editor (in this case Sublime Text) to modify README.md

![github five step example](https://i.imgur.com/SMlvRYL.png)


---

-> The 6 Step is add in the branch [ -> 01-Example <- ] the README.md with this command.

> ( -> git add README.md <- ) <

![github six step example](https://miro.medium.com/max/1668/1*zLxE3Deuc2ePubedcXvlnQ.png)


---

-> The 7 Step is check the status again with the same command that we used. 
> ( -> git status <- ) < 

-> We can see that the changes in the file is commited.

![github seven step example](https://styde.net/wp-content/uploads/2015/04/git-add-all-status.png)


---

-> The 8 Step is use this command to create a comment in the file.
> ( -> git commit -v <- ) <

![github](https://i.stack.imgur.com/G2b0d.png)

or

> ( -> git commit -v "Add new content to README.md" <- ) <

![github](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT0MEFQeDtkDiNHeBt_skTFQi6sO0W1uQ5KnA&usqp=CAU)


---

-> The 9 Step is check status again to watch what changes are in the file, in this case, we don't change anything.

---

-> The 10 Step is Push the branch to the Repository. For this step we need to use this command.

> ( -> git push origin 01-Example <- )

![github push origin](https://i.stack.imgur.com/SKoea.png)


---

-> The 11 Step is write our account and password of github.

---

-> The 12 Step is change of branch, in this case, we are going to change to the first branch that we created. [ -> SPRINT-02 <- ].

> ( -> git checkout SPRINT-02 <- ) <

or

> ( -> git co SPRINT-02 <- ) < [Is the same |co|  than |checkout|]

![github branch](https://www.jquery-az.com/wp-content/uploads/2018/06/2.0_3-Git-checkout-branch.png)


---

-> The 13 Step is push the branch [ -> SPRINT-02 <- ].

> ( -> git push origin SPRINT-02 <- ) <

![github push sprint-02](https://david-estevez.gitbooks.io/the-git-the-bad-and-the-ugly/content/assets/04_git_push.png)


---

-> The 14 Step is compare the First Branch with the Second Branch in the repository.

-> [ (SPRINT-02) compare to (01-Example) ] <-

![github compare](https://docs.github.com/assets/images/help/pull_requests/pull-request-review-edit-branch.png)


---

-> The 15 Step is create a pull request.

![github pull request](https://zellwk.com/images/2018/submit-pr/pull-request-open.png)


---

-> The 16 Step is do the merge pull request and confirm them.

![github merge](https://www.earthdatascience.org/images/earth-analytics/git-version-control/github-close-pull-request.png)

---

![github confirm merge](https://docs.github.com/assets/images/help/pull_requests/merge_box/pullrequest-commitmessage.png)


---

-> The 17 Step is change the branch in the repository and check the branches that we have to elimine the 01-Example branch. 

![github eliminate branch](https://explainexampleimages.s3.ap-south-1.amazonaws.com/delete-git-branch/delete-git-branch-remotely-ui.PNG)


---

-> The 18 Step is eliminate the branch in the terminal.

> ( -> git branch -d 01-Example <- ) < 

![github eliminate](https://linuxconfig.org/images/01-git-delete-branch.png)



:D and that's all.
