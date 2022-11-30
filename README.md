# get-template
Download any template for your project

### How to use
````sh
npx get-template <template> [<download-directory>]
````

This will download a template in the directory you want. By default, the download directory will be the current one (i.e. `.`).

Template names are GitHub's username and repository name. So, if you want to download the template from https://github.com/github/codespaces-react, your command would be:

````sh
npx get-template github/codespaces-react
````

To download it in an specific directory, your command would be:
````sh
npx get-template github/codespaces-react my-folder-name
````

The directory **must** be empty. If not, it won't download the template

### Aliases
To make templates easier to download, you can use aliases. These aliases simplify how people download templates.

For example, the alias `package` downloads a template to [create TypeScript packages](https://github.com/itaibo/package-template):

````sh
npx get-template package
````

You can propose new alias in the [aliases repository](https://github.com/get-template/aliases)
