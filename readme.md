# Microsoft DevOps
This repo is for DevOps data-sheets - quick "bites" that showcase how companies used
DevOps practices to solve some business problem, from increasing time to delivery
to improving quality.

### Process
Each story is a mini white paper for a particular company. Data is received from
Microsoft TE's that interview the customer in some manner. The ineterviews are 
then collated into a document using the [FabrikamFiber Devops](/Final/FabFiber%20DevOps.docx)
document as a guide.

### TE Instructions
In order to make changes to this repo, you must fork the repo. Log into Github, 
browse to this repo and select "Fork" in the top-right.

Once you have forked the repo, you can clone it locally. Make your changes and 
then push them to your forked repo. Then you can create a Pull Request and the
repo owners will review your changes.

The folling commands can be used to clone, commit and push changes once you 
have forked the repo.

> **Note:** All the commands must be performed from the root folder of the repo.

1. Once you have interviewed a customer, fork this repo. This creates a copy of
the repo under your own Github account. This is the only way to make changes to
the repo.

1. Clone the forked repo.
	```
	git clone url_of_your_forked_repo
	```

1. If you have already cloned the repo, make sure you are on the `master` branch
and pull the latest repo.

	```
	git checkout master
	git pull
	```

1. Make your changes.
1. Under the `Interviews and Raw Data` folder, create a new folder with the name 
of the customer (e.g. FabrikamFiber).
1. Copy the interview documents, logos and any other pertinent material into this
folder.
1. Add the final white-paper for the customer to the `Final` folder.
1. When you are ready to publish your new files and edits, you need to add the files
to the local git repo.

	```
	git add .
	```

1. Commit, using `-m` to add a commit message:

	```
	git commit -m "Adding files for Fabrikam"
	```

1. Publish the branch to Github (use the same name as your local branch):

	```
	git push
	```

1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/)
for the fork on Github.