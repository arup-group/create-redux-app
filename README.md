# CREATE REDUX APP

Uses (ArupAus/React-App-Template)[https://github.com/ArupAus/react-app-template] to create a template redux application

## REQUIREMENTS

You will need to have a valid SSH key for the ArupAus organisation to properly install/run the node commands. (Click here to learn more.)[https://help.github.com/en/articles/connecting-to-github-with-ssh]

## RUN (WITHOUT INSTALL)

If you prefer to not install the package globally you can instead run the single line command  
`npx git+ssh://git@github.com/ArupAus/create-redux-app.git <project-name>`  
Where `<project-name>` is the name of the project you want to create

## INSTALL & RUN

`npm install -g git+ssh://git@github.com/ArupAus/create-redux-app.git`

`create-redux-app <project-name>`

## DEV

To make changes to this project and test them, it is reccomended to clone the repo as you normally would, then link the package locally so that you can immediately run the updated version.  
e.g. `npm link` in the create-redux-app folder.

When you have finished ensure that you have tidied up your dev environment by unlinking the local package.  
e.g. `npm unlink` in the create-redux-app folder.
