
### 4. How to set up Git and work collaboratively with more than one person:

#### Step 1. Create a Repository
A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs. It is recommended to include a README, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.

For example, “IS601_Project_1” is the repository we created for mini project. This repository can be a place to store ideas, resources, or even share and discuss things with others.

<strong>To create a new repository</strong>

In the upper right corner, next to your avatar or identicon, click and then select New repository.

Name the repository “IS601_Project_1”.

Write a short description.

Select Initialize this repository with a README.

Click Create repository.

#### Step 2. Create a Branch
Branching is the way to work on different versions of a repository at one time.

By default, repository has one branch named “main” which is the definitive branch. We use branches to experiment and make edits before committing them to “main” branch.

When you create a branch off the “main” branch, we are making a copy, or snapshot, of main as it was at that point in time. If someone else made changes to the “main” branch while you were working on your branch, you could pull in those updates.

Below Diagram shows:

The main branch

A new branch called “feature” (because we are doing ‘feature work’ on this branch)

The journey that “feature” takes before it’s merged into main
 
We can save different versions of a file. Something like:
Basic_Git_Commands.doc
Basic_Git_Commands edited.doc
Updated Basic_Git_Commands edited.doc

Branches accomplish similar goals in GitHub repositories.
In GitHub, developers, writers, and designers can use branches for keeping bug fixes and feature work separate from main (production) branch. When a change is ready, we can merge the branch into main.

<strong>To create a new branch:</strong>
<ol>
 <li>Go to your new repository “IS601_Project_1”.</li>
 <li>Click the drop down at the top of the file list that says branch: main.</li>
 <li>Type a branch name, “feature” into the new branch text box.</li>
 <li>Select the blue Create branch box or hit “Enter” on your keyboard.</li>
 </ol>
Now we have two branches, main and feature. They look exactly the same, but not for long! Next, we will add our changes to the new branch.

#### Step 3. Make and commit changes

Now, we are on the code view for “feature” branch, which is a copy of main and we can make some edits.

On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you have done and why.

<strong>Make and commit changes</strong>

Click the README.md file.

Click the pencil icon in the upper right corner of the file view to edit.

In the editor, write a bit about your project and about teammates.

Write a commit message that describes your changes.

Click Commit changes button.

These changes will be made to just the README file on your feature branch, so now this branch contains content that is different from main.

#### Step 4. Open a Pull Request

Now that we have changes in a branch off of main, we can open a pull request.

Pull Requests are the heart of <strong><em>collaboration</em></strong> on GitHub. When you open a pull request, you are proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

By using GitHub’s @mention system in your pull request message, you can ask for feedback from specific people or teams, whether they are down the hall or 10 time zones away.

You can even open pull requests in your own repository and merge them yourself. It is a great way to learn the GitHub flow before working on larger projects.

<strong>Open a Pull Request for changes to the README:</strong>
> 1. Click the Pull Request tab, then from the Pull Request page, click the green New pull request button.</li>
> 2. Select the branch you made, feature, to compare with main (the original).</li>
> 3. Look over your changes in the diffs on the Compare page, make sure they are what you want to submit.
> 4. When you are satisfied that these are the changes you want to submit, click the big green Create Pull Request button.
> 5. Give your pull request a title and write a brief description of your changes.
> 6. When you are done with your message, click Create pull request.
 
#### Step 5. Merge your Pull Request
In this final step, it is time to bring your changes together – merging your “feature” branch into the “main” branch.

Click the green Merge pull request button to merge the changes into main.

Click Confirm merge.

Go ahead and delete the branch, since its changes have been incorporated, with the Delete branch button in the purple box.

