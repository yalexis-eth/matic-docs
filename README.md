<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/25497083/156289024-df2c8970-2072-4439-813d-d38809e80eef.png" width="200">
</p>

<div align="Center">
<h1>Polygon Wiki</h1>
<h3> Previously Matic Network </h3>
</div>

<br>

![Forks](https://img.shields.io/github/forks/maticnetwork/matic-docs?style=social)
![Stars](https://img.shields.io/github/stars/maticnetwork/matic-docs?style=social)
![Languages](https://img.shields.io/github/languages/count/maticnetwork/matic-docs)
![Issues](https://img.shields.io/github/issues/maticnetwork/matic-docs)
![PRs](https://img.shields.io/github/issues-pr-raw/maticnetwork/matic-docs)
![contributors](https://img.shields.io/github/contributors-anon/maticnetwork/matic-docs)
![size](https://img.shields.io/github/languages/code-size/maticnetwork/matic-docs)
[![Discord](https://img.shields.io/discord/714888181740339261?color=1C1CE1&label=Polygon%20%7C%20Discord%20%F0%9F%91%8B%20&style=flat-square)](https://discord.gg/zdwkdvMNY2)
[![Twitter Follow](https://img.shields.io/twitter/follow/0xPolygon.svg?style=social)](https://twitter.com/0xPolygon)

Polygon is a scaling solution for public blockchains that combines the best of Ethereum and sovereign blockchains 
to offer a full-stack scaling solution.

The [Polygon Wiki](https://docs.polygon.technology/) is built using [Docusaurus](https://docusaurus.io/), 
a modern static website generator to build optimized websites quickly.

## How to Contribute to Polygon Wiki

We believe one of the things that makes Polygon unique is its coherent design, and we seek to retain this defining 
characteristic. We have defined some guidelines to ensure new contributions only ever enhance the 
Wiki from the outset.

### Requirements

* Install [Node.js](https://nodejs.org/en/download/) version >= 12.13
* Install [Yarn](https://yarnpkg.com/getting-started/install) version >= 1.5  

> Note that on macOS you also need Xcode and Command Line Tools.

### Run the Wiki locally

1. Fork the repo. 
   > For help, refer to [GitHub Docs: Fork a repo](https://help.github.com/en/articles/fork-a-repo).
   
2. Clone your forked repo.
   
    ```
    git clone git@github.com:[your_github_handle]/matic-docs
    ```

3. Navigate into the cloned folder.
   
    ```
    cd matic-docs
    ```

4. Link your cloned repo to the upstream repo.
   > For help, see [GitHub Docs: Configuring a remote for a fork](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork).
   
    ```
    git remote add upstream https://github.com/maticnetwork/matic-docs
    ```

5. If you have already cloned the repository, be sure to sync your fork with the latest changes. 
   > For help, refer to [GitHub Docs: Syncing a fork](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork).

    ```
    git checkout master
    git fetch upstream
    git merge upstream/master
    ```

6. Install the dependencies.
   
    ```
    yarn install
    ```
    
   The site is built using Docusaurus. You may need to install Docusaurus before running the Wiki locally.

   ```
   yarn add docusaurus
   ```
   
   Alternatively, you can upgrade Docusaurus.

   ```
   yarn upgrade @docusaurus/core@latest @docusaurus/preset-classic@latest
   ```

7. Run the Wiki locally. 
   The following command will start a local development server and open a browser window. 
   Most changes are reflected live without having to restart the server.

    ```
    yarn start
    ```

### Make changes using Git GUI and code editor

After running the Wiki locally on your machine, use a code editor to apply your changes before submitting 
your PR. Note that you must have a GitHub account and an understanding of Markdown syntax.

1. Create a new branch for your changes.
   
    ```
    git checkout -b [new_branch_name]
    ```

2. Commit your changes. Please be sure to review our [Git Rules](https://docs.polygon.technology/docs/contribute/orientation#git-rules). 
   In the commit message, please reference the issue it resolves. 
   For help, see [GitHub Docs: Linking a pull request to an issue using a keyword](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword).

    ```
    git commit -m "brief description of changes [Fixes #1234]"
    ```

3. Push to your forked repository.
   
    ```
    git push
    ```

4. Submit a PR against the `master` branch of the `maticnetwork/matic-docs` repo
   
5. Add a title to your PR. 
   > For example, if you want to suggest edits to the "Getting Started" page, name your PR: *Update /docs/develop/getting-started.md*.
   
6. Add a description to your PR. Please reference the issue it resolves. 
   > For help, see [GitHub Docs: Linking a pull request to an issue using a keyword](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword).
   
7. Write a brief description of the changes you have made. If possible, include screenshots and references.

You can apply UI changes, sidebar, and configuration design through the following files:

- To modify the **Sidebar** navigation, edit **sidebars.js**
- To modify the website page layout, edit **docusaurus.config.js**
- To modify the blocks structure and the footer links, edit **src/pages/index.js**

### Making changes using the Wiki website

You can easily submit an edit suggestion. Note that you must have a GitHub account and good knowledge of Markdown syntax.

1. Navigate to the [Polygon Wiki page](https://docs.polygon.technology/) that you want to edit.
2. Scroll down until the end of that page
3. Click on the link: **Edit this page**. It will forward you to the same page (Markdown format) hosted on GitHub.
4. On the related GitHub page, click the pencil icon (similar to  ) near the upper right corner of the file
5. Apply your edits by modifying the Markdown file
6. After you finish, scroll down until the end of that page to create a pull request 
7. Add a title to your PR. For example, if you want to suggest edits to the "Getting Started" page, name your PR: 
   *Update /docs/develop/getting-started.md*.
8. Add a description to your PR. Please reference the issue it resolves. 
   > For help, see [GitHub Docs: Linking a pull request to an issue using a keyword](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword).
9.  Write a brief description of the changes you have made. If possible, include screenshots and references.
10. Click on the green button **Propose changes** to submit your changes. Note that submitting a change will write 
    it to a new branch in your fork.

One of the Wiki maintainers will review your PR and either accept it or submit our review. 
Acceptable PRs will be approved & merged into the `master` branch.

## Submit an Issue

- Create a [new issue](https://github.com/maticnetwork/matic-docs/issues/new/choose) to report a bug, request a feature, 
  or suggest changes.
- Comment on the issue if you want to be assigned to it so [our team can assign the issue to you](https://github.blog/2019-06-25-assign-issues-to-issue-commenters/).
- If you do not have a specific contribution in mind, you can also browse current issues.
- Issues that additionally have the `good first issue` label are considered ideal for first-timers.

## Build

This command generates static content into the `build` directory and can be served using any static content hosting 
service:

```
yarn build
```

## Deployment

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the 
`gh-pages` branch.

```
GIT_USER=[your_github_handle] USE_SSH=true yarn deploy
```
