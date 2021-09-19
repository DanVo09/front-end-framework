# Basic Framework For Front End Vanilla.js Projects

## Preflight Check
1. Run npm install from the framework root folder. This will create the node_modules and install the dependancies found in the package.json file.
```bash
  npm install
```

1. Run development build using the parcel bundler.
```bash
   npx parcel src/index.html
```
or
```
  npm start
```

1. Run production build using the parcel bundler.
```bash
   npx parcel build src/index.html
```
or
```
  npm run build
```

## GIT SETUP
1. .gitignore ignores files and they will not be uploaded to remote repository.

1. Set up repo from VS Code
1. User Profile Icon
1. Sign in to sync settings
1. Sign in with github
1. Click the green button to accept
1. Click on the Source Control Tab
1. Publish To Git Select Public Reop
1. Publish the folder to the github repo

## Remove Repo
1. Go to the Github repo
1. Select settings
1. Scroll to the bottom
1. Delete the repo

# Deploying To Netlify
1. Account at netlify log in.
1. Click on team name select sites tab.
1. Site click on the deploy from git
1. Select GitHub
1. Show your repo's
1. Select the repo to build
1. Make sure to write the correct build command.
```
parcel build src/index.html

```
1. Netlify will deploy the repo.

# VS CODE
1. Make changes
1. Commit the changes
1. Push the changes to remote repo.
1. Netlify see's changes and build a new site.
