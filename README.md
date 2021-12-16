# GitHub repository set up check list

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

## Add code analysis

To set up code analysis, Goto **_Settings_** -> **_Security & analysis_** -> **_Code scanning_**. Then you can either select [CodeQL](https://codeql.github.com/) Analysis by GitHub or another security analysis from the GitHub Marketplace.

## Resources

- [GitHub Actions](https://docs.github.com/en/actions)
- [Workflow syntax for GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/workflow-syntax-for-github-actions)
- [GitHub Actions - setup dotnet](https://github.com/actions/setup-dotnet)
- [dotnet restore](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-restore)
- [dotnet build](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-build)
- [dotnet test](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-test)
- [CodeQL Docs](https://codeql.github.com/docs/codeql-overview/)
