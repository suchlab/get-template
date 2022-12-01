# get-template
![CI](https://github.com/get-template/get-template/actions/workflows/ci.yml/badge.svg)

Download any template for your project

## How to use
````sh
npx get-template <template> [<download-directory>] [--execute-commands] [--keep-git]
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

The get-template tool removes the .git folder by default. To keep the original template's git, add the flag `--keep-git`:

````sh
npx get-template package --keep-git
````

## Aliases
To make templates easier to download, you can use aliases. These aliases simplify how people download templates.

For example, the alias `package` downloads a template to [create TypeScript packages](https://github.com/itaibo/package-template):

````sh
npx get-template package
````

Aliases can include post-download commands to be executed (e.g. `npm install`). If you want to execute these commands, add the flag `--execute-commands`:

````sh
npx get-template package --execute-commands
````

You can propose new aliases in the [aliases repository](https://github.com/get-template/aliases)

## Popular templates
These are some popular templates you can download using get-template. Not only for JavaScript projects!

- [get-template/react-app-template](https://github.com/get-template/react-app-template) `npx get-template react-app`
- [coreui/coreui-free-react-admin-template](https://github.com/coreui/coreui-free-react-admin-template) `npx get-template coreui-free-react-admin`
- [github/codespaces-react](https://github.com/github/codespaces-react) `npx get-template github/codespaces-react`
- [serverless/examples](https://github.com/serverless/examples) `npx get-template serverless/examples`
- [prisma/prisma-examples](https://github.com/prisma/prisma-examples) `npx get-template prisma/prisma-examples`
- [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) `npx get-template h5bp/html5-boilerplate`
- [ColorlibHQ/AdminLTE](https://github.com/ColorlibHQ/AdminLTE) `npx get-template ColorlibHQ/AdminLTE`
- [akveo/ngx-admin](https://github.com/akveo/ngx-admin) `npx get-template akveo/ngx-admin`
- [async-labs/saas](https://github.com/async-labs/saas) `npx get-template async-labs/saas`
- [kriasoft/react-starter-kit](https://github.com/kriasoft/react-starter-kit) `npx get-template kriasoft/react-starter-kit`
- [dhg/Skeleton](https://github.com/dhg/Skeleton) `npx get-template dhg/Skeleton`

## Pro tip
Alternatively, you can use these npm/npx aliases:

```sh
# Original command
npx get-template package .

# gete (flags not allowed yet)
npx gete package .

# gette (flags not allowed yet)
npx gette package .
```

## People
The original author of get-template is [itaibo](https://github.com/itaibo)

You can contribute too!
