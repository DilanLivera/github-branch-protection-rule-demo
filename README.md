# GitHub branch protection rule demo

## Add a CODEOWNERS file to the repository

CODEOWNERS file defines the people who are the owers of the code in the repository. To add a CODEOWNERS file to a repository, create a file with the name CODEOWNERS in the root, `docs/` or `.github/` directory of the repository. According to GitHub docs,

> Each CODEOWNERS file assigns the code owners for a single branch in the repository. Thus, you can assign different code owners for different branches, such as @octo-org/codeowners-team for a code base on the default branch and @octocat for a GitHub Pages site on the gh-pages branch.

Read more about code owners at [About code owners](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)

## Set up merging

To set up merging, Goto **_Settings_** -> **_Options_** -> **_Merge button_**.

Don't forget to check the box for **_Automatically delete head branches_** if you wish to have head branches deleted automatically after merging the pull requests.

## Add branch protection rule

To add a brach protection rule, Goto **_Settings_** -> **_Branches_** -> **_Add rule_**.

1. Add a pattern of the branches to which the rule should apply.

2. Check the required rules

3. Click **_Create_**
