# get-template
![CI](https://github.com/get-template/get-template/actions/workflows/ci.yml/badge.svg)

Download any template for your project

## How to use
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

## Aliases
To make templates easier to download, you can use aliases. These aliases simplify how people download templates.

For example, the alias `package` downloads a template to [create TypeScript packages](https://github.com/itaibo/package-template):

````sh
npx get-template package
````

You can propose new alias in the [aliases repository](https://github.com/get-template/aliases)

## Popular templates
These are some popular templates you can download using get-template. Not only for JavaScript projects!

- [github/gitignore](https://github.com/github/gitignore) `npx get-template github/gitignore`
- [sveltejs/svelte](https://github.com/sveltejs/svelte) `npx get-template sveltejs/svelte`
- [react-boilerplate/react-boilerplate](https://github.com/react-boilerplate/react-boilerplate) `npx get-template react-boilerplate/react-boilerplate`
- [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) `npx get-template h5bp/html5-boilerplate`
- [ColorlibHQ/AdminLTE](https://github.com/ColorlibHQ/AdminLTE) `npx get-template ColorlibHQ/AdminLTE`
- [akveo/ngx-admin](https://github.com/akveo/ngx-admin) `npx get-template akveo/ngx-admin`
- [kriasoft/react-starter-kit](https://github.com/kriasoft/react-starter-kit) `npx get-template kriasoft/react-starter-kit`
- [dhg/Skeleton](https://github.com/dhg/Skeleton) `npx get-template dhg/Skeleton`

## People
The original author of get-template is [itaibo](https://github.com/itaibo)

You can contribute too!
