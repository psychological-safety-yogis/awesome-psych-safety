# Guides online:

[Jetbrains "A Guide to Perfecting Pull Requests"](https://www.jetbrains.com/help/mps/work-with-github-pull-requests.html#apply-pull-request-changes)

[Making a Pull Request](https://www.atlassian.com/git/tutorials/making-a-pull-request)

[Github's best practices](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/best-practices-for-pull-requests)

[Github's collaborating with pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests)

[How to Create a Pull Request in GitHub *Correctly*](https://genicsblog.com/gouravkhunger/how-to-create-a-pull-request-in-github-correctly)

"A guide that teaches you how to fork a GitHub repository, make changes and create pull requests in the correct way."


## Basically: 

In the file name field:

To make your pull request template visible in the repository's root directory, name the pull request template pull_request_template.md.
To make your pull request template visible in the repository's docs directory, name the pull request template docs/pull_request_template.md.
To store your file in a hidden directory, name the pull request template .github/pull_request_template.md.
To create multiple pull request templates and use the template query parameter to specify a template to fill the pull request body, type .github/PULL_REQUEST_TEMPLATE/, then the name of your pull request template. For example, .github/PULL_REQUEST_TEMPLATE/pull_request_template.md. You can also store multiple pull request templates in a PULL_REQUEST_TEMPLATE subdirectory within the root or docs/ directories. For more information, see "Using query parameters to create a pull request."
In the body of the new file, add your pull request template. This could include:

A reference to a related issue in your repository.
A description of the changes proposed in the pull request.
@mentions of the person or team responsible for reviewing proposed changes.
Click Commit changes...

In the "Commit message" field, type a short, meaningful commit message that describes the change you made to the file. You can attribute the commit to more than one author in the commit message. For more information, see "Creating a commit with multiple authors."

Below the commit message fields, decide whether to add your commit to the current branch or to a new branch. If your current branch is the default branch, you should choose to create a new branch for your commit and then create a pull request. For more information, see "Creating a pull request."

Screenshot of a GitHub pull request showing a radio button to commit directly to the main branch or to create a new branch. New branch is selected.
Templates are available to collaborators when they are merged into the repository's default branch.

Click Commit changes or Propose changes.



## or, basically: 



Creating a pull request
In this article
Changing the branch range and destination repository
Creating the pull request

Create a pull request to propose and collaborate on changes to a repository. These changes are proposed in a branch, which ensures that the default branch only contains finished and approved work.

Who can use this feature
Anyone with read access to a repository can create a pull request.

If you want to create a new branch for your pull request and do not have write permissions to the repository, you can fork the repository first. For more information, see "Creating a pull request from a fork" and "About forks."

You can specify which branch you'd like to merge your changes into when you create your pull request. Pull requests can only be opened between two branches that are different.

Note: To open a pull request in a public repository, you must have write access to the head or the source branch or, for organization-owned repositories, you must be a member of the organization that owns the repository to open a pull request.

You can link a pull request to an issue to show that a fix is in progress and to automatically close the issue when someone merges the pull request. For more information, see "Linking a pull request to an issue."

Changing the branch range and destination repository
By default, pull requests are based on the parent repository's default branch. For more information, see "About branches."

If the default parent repository isn't correct, you can change both the parent repository and the branch with the drop-down lists. You can also swap your head and base branches with the drop-down lists to establish diffs between reference points. References here must be branch names in your GitHub repository.

Screenshot of a pull request. The dropdown to edit the compare branch is expanded.

When thinking about branches, remember that the base branch is where changes should be applied, the head branch contains what you would like to be applied.

When you change the base repository, you also change notifications for the pull request. Everyone that can push to the base repository will receive an email notification and see the new pull request in their dashboard the next time they sign in.

When you change any of the information in the branch range, the Commit and Files changed preview areas will update to show your new range.

Tips:

Using the compare view, you can set up comparisons across any timeframe. For more information, see "Comparing commits."
Project maintainers can add a pull request template for a repository. Templates include prompts for information in the body of a pull request. For more information, see "About issue and pull request templates."
Creating the pull request
On GitHub.com, navigate to the main page of the repository.

In the "Branch" menu, choose the branch that contains your commits.

Screenshot of the branch dropdown menu on the main page of a repository.

Above the list of files, in the yellow banner, click Compare & pull request to create a pull request for the associated branch.

Screenshot of the banner above the list of files.

Use the base branch dropdown menu to select the branch you'd like to merge your changes into, then use the compare branch drop-down menu to choose the topic branch you made your changes in.

Type a title and description for your pull request.

To create a pull request that is ready for review, click Create Pull Request. To create a draft pull request, use the drop-down and select Create Draft Pull Request, then click Draft Pull Request. For more information about draft pull requests, see "About pull requests."

Tip: After you create a pull request, you can ask a specific person to review your proposed changes. For more information, see "Requesting a pull request review."

After your pull request has been reviewed, it can be merged into the repository.

