## Boilerplate based on create-react-app

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find some information on how to perform common tasks.<br>
You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Dependencies that was added to this app

None.

## Quick start
**1.** Clone project
```bash
# with SSH
git clone git@github.com:wkdtjsgur100/boilerplate-using-create-react-app.git NEW_PROJECT_NAME

# with HTTPS
git clone https://github.com/wkdtjsgur100/boilerplate-using-create-react-app.git NEW_PROJECT_NAME
```

**2.** Go inside project folder `cd NEW_PROJECT_NAME` and Command `git reset --hard COMMIT_ID` by commit message, COMMIT_ID is commit id what you want to use.

```bash
git reset --hard COMMIT_ID
```

**3.** Edit project name inside `package.json`
```javascript
// change
{
  "name": "boilerplate-using-create-react-app",  
}

// to the
{
  "name": "NEW_PROJECT_NAME",  
}
```

**4.** Delete .git folder
```bash
# command for Mac/Linux
rm -rf .git

# command for Windows
rmdir .git
```

**5.** Initialize new git
```bash
git init
git add .
git commit -m "[initial commit] NEW_PROJECT_NAME"
```

**6.** npm install
``` bash
npm install
```

## Improved folder Structure

Same as [@create-react-app](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#folder-structure)

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](#running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](#deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.
