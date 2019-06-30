This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Steps
* Step 1. Create a new repo on Github.
* Step 2: Clone the Repo to your local machine.
git clone https://github.com/JJAshcraft/netlify-guide-react.git test-repo
* Step 3. Change to your repo directory and run create-react-app.
create-react-app myapp
* Step 4. Add your First Changes.
git status
git add .
git commit -m'Initial Commit, creates new react app with create-react-app'
git push
* Step 5. Create a New Branch on your Repo
git checkout -b netlify-deploy
git branch
* Step 6. Create the toml file.
* Step 7. Add the build information to your toml file.

[build]
base = "myapp/"
publish = "myapp/build/"
command = "yarn build"
* Step 8. Commit your New Changes.
git status
git add .
git commit -m'adds netlify.toml for continuous deployment settings'
* Step 9. UH OH! We broke it.
git push --set-upstream origin netlify-deploy
* Step 10. Let’s Create our Pull Request.
 and merge pull request
* Step 11. Open a Browser Window, and go to Netlify.com

* Step 12. Choose a Repo to Deploy.
* Step 13. Click 'Deploy Site'.

[Ref]
https://hackernoon.com/netlify-continuous-deployment-github-react-lambdaschool-67f3ae658d31
## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
