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
> **Note:** All the commands must be performed from the root folder of the repo.

1. Once you have interviewed a customer, clone this repo.
1. If you have already cloned the repo, make sure you are on the `master` branch
and pull the latest repo.

	```
	git checkout master
	git pull
	```

1. Create a new branch using the customer name as the branch name (e.g. Fabrikam)

	```
	git checkout -b Fabrikam
	```

1. Under the `Interviews and Raw Data` folder, create a new folder with the name 
of the customer (e.g. FabrikamFiber).
1. Copy the interview documents, logos and any other pertinent material into this
folder.
1. Add the files.

	```
	git add .
	```

1. Commit, using `-m` to add a commit message:

	```
	git commit -m "Adding files for Fabrikam"
	```

1. Publish the branch to Github (use the same name as your local branch):

	```
	git push -u origin Fabrikam
	```

1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/)
for the branch on Github.