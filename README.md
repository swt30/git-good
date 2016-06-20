# Sample repository

This is a sample repository for you to practise your Git skills on.
Try cloning the repository to your local machine first.
Once you've done that, try making a modification to it and commiting it.
Then look through the log and see if you can find some pictures of cats that I added and then removed in earlier commits.
Check out the first of these commits and verify that the cat pictures are there.

## What next?

At this stage the repository is yours to do what you want. 
You can make your own commits and pull in any changes. 
In fact, if I were to make you a collaborator, you could push your changes to the copy of the repository on github. 
But that's not always the case. 
Many open source projects have a core group of developers but still want to solicit improvements from the wider community. 
However, there needs to be a way for core developers to review these changes. 
This mechanism is known as a "pull request" -- you make a *request* for me to *pull* a set of changes into my repository.

We probably won't have time to try out pull requests, but if we do, here are the instructions: 

## How to make a pull request

1. *Fork* my repository on github. This gives you your own version which will show up under your username.
2. *Clone* your fork to your local machine: `git clone https://github.com/username/repo.git`
3. Make a *new branch*: `git checkout -b branch-name`. Any changes you commit to this branch will leave the master branch unchanged. It is good practice to create a new branch for each discrete feature or change you want to make.
4. Make and commit your changes.
5. Push your branch: `git push --set-upstream origin branch-name`
6. Go to your repository on github and see if the branch is listed. You should be given the option to create a pull request, which will send your change to me for approval. I can then pull your change into my master branch, making it available to everyone.

You can also do this directly from github! Look for the pencil symbol, which lets you edit files - like this README - and submit a pull request directly. This is a quick and easy way to make small changes. Give it a try

# This section reserved for your changes

I sure do love learning how to use git. I wonder what zany things others will add after this line?
Hey .astronomy, how it's going?

Hey Scott! .Astronomy is feeling good this morning!
