# 1 - Project Setup

Start by creating a directory for this project

```shell
cd <WorkspaceFolder>
mkdir react-webpack-linting-starter
cd react-webpack-linting-starter
```

Inside of the project folder let’s create a couple of directories and files

```shell
mkdir public src
touch public/index.html
touch src/index.js
```

Once you have created the folder, and the files let’s initialize a Git repository so we don’t lose our place and initialize npm so we have our `package.json`.

```shell
git init
npm init -y # We don't care much about the project info at this point
```

Now that we have git and npm sorted, let’s open up the project in VS Code and start coding.

Inside of the `public/index.html` file, write the following boilerplate

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>React from Scratch</title>
  </head>
  <body>
    <noscript>You need to enable Javascript to run this application</noscript>
    <script src="../dist/bundle.js"></script>
  </body>
</html>
```

You’ll notice that we are not connecting the `src/index.js` file that we created earlier. We’ll explain why later in the lesson. For now, let’s get Webpack installed.

---

## Current folder structure

Before we move on, double check that you folder structure looks like this.

```
├── public
│   └── index.html
├── src
│   └── index.js
├── package-lock.json
└── package.json
```

---

[Next Module >>>](../2-webpack-config)
