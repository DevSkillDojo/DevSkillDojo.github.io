# Using Foam

# Generating the site

## Local Generation
Foam is GitHub-pages ready as-is. However, you will likely want to build a local copy. If so, simply install the relevant pages for generating GitHub pages locally. Find the details here: [Setting up your GitHub Pages locally with Jekyll](https://docs.github.com/en/enterprise/2.14/user/articles/setting-up-your-github-pages-site-locally-with-jekyll)

In short:
 - Ensure ruby is installed
 - Install Jekyll and other depedencies with: "bundle install" from the root of the repo
 - Server the local site with "bundle exec jekyll serve" from the root of the repo

## GitHub Pages
The GitHub repo is configured to build automatically from the master branch. To to publish changes, just merge a PR

# Setting up

This documentation assumes that you have a GitHub account and have [Visual Studio Code](https://code.visualstudio.com/) installed on your Linux/MacOS/Windows machine.

1. If you haven't yet, browse over to the main [Foam documentation workspace](https://foambubble.github.io/foam) to get an idea of what Foam is and how to use it.
2. Press "Use this template" button at [foam-template](https://github.com/foambubble/foam-template/generate) (that's this repository!) to fork it to your own GitHub account. If you want to keep your thoughts to yourself, remember to set the repository private.
3. [Clone the repository to your local machine](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) and open it in VS Code.

    *Open the repository as a folder using the `File > Open...` menu item. In VS Code, "open workspace" refers to [multi-root workspaces](https://code.visualstudio.com/docs/editor/multi-root-workspaces).*

4. When prompted to install recommended extensions, click **Install all** (or **Show Recommendations** if you want to review and install them one by one)

After setting up the repository, open [.vscode/settings.json](.vscode/settings.json) and edit, add or remove any settings you'd like for your Foam workspace.

To learn more about how to use **Foam**, read the [Recipes](https://foambubble.github.io/foam/recipes) bubbles of the Foam documentation workspace.

## Note on `[[wiki-links]]`

⚠️ Until [foambubble/foam#16](https://github.com/foambubble/foam/issues/16) is resolved, `[[wiki-links]]` links (like the links above) won't work in the GitHub Markdown preview (i.e. this Readme on github.com).

They should work as expected in VS Code, and in rendered GitHub Pages.

If GitHub preview (or general 100% support with all Markdown tools) is a requirement, for the time being you can use the standard `[description](page.md)` syntax.

# Foam Recipes
_For up-to-date tips, see [Foam Recipes](https://foambubble.github.io/foam/recipes)._

