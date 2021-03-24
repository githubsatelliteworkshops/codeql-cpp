<h1 align="center">Finding security vulnerabilities with CodeQL</h1>
<h5 align="center">@ammohant and @ds-ms</h5>
<h5 align="center">Moderated by: @ganeshrockz and @shigupt202 </h5>


<p align="center">
  <a href="#mega-prerequisites">Prerequisites</a> •  
  <a href="#books-resources">Resources</a>
</p>

> CodeQL is GitHub's expressive language and engine for code analysis, which allows you to explore source code to find bugs and security vulnerabilities. During these beginner-friendly workshops, you will learn to write queries in CodeQL and find known security vulnerabilities in open-source Java and JavaScript projects.

## :mega: Prerequisites
- Install [Visual Studio Code](https://code.visualstudio.com/).
- Install the [CodeQL extension for Visual Studio Code](https://help.semmle.com/codeql/codeql-for-vscode/procedures/setting-up.html).
- You do _not_ need to install the CodeQL CLI: the extension will handle this for you.
- Set up the [CodeQL starter workspace](https://help.semmle.com/codeql/codeql-for-vscode/procedures/setting-up.html#using-the-starter-workspace).
  - **Important:** Don't forget to use `git clone --recursive` or `git submodule update --init --remote` to update the submodules when you clone this repository. This allows you to obtain the standard CodeQL query libraries.
  - Open the starter workspace in Visual Studio Code: **File** > **Open Workspace** > Browse to `vscode-codeql-starter/vscode-codeql-starter.code-workspace` in your checkout of the starter workspace.
- Download and add the CodeQL database to be used in the workshop:
  - Please download [this CodeQL database](https://github.com/githubsatelliteworkshops/codeql-workshop-satellite/blob/master/example_db.zip).
  - Unzip the database.
  - Import the unzipped database into Visual Studio Code:
    - Click the CodeQL icon in the left sidebar.
    - Place your mouse over **Databases**, and click the `+` sign that appears on the right.
    - Choose the unzipped database directory on your filesystem.

## :books: Resources
- [Learning CodeQL](https://help.semmle.com/QL/learn-ql)
- [Learning CodeQL for CPP](https://codeql.github.com/docs/codeql-language-guides/codeql-for-cpp/)
- [Using the CodeQL extension for VS Code](https://help.semmle.com/codeql/codeql-for-vscode.html)
- More about CodeQL on [GitHub Security Lab](https://securitylab.github.com/tools/codeql)
- CodeQL on [GitHub Learning Lab](https://lab.github.com/githubtraining/codeql-u-boot-challenge-(cc++))
