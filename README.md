# Intern Dev Task

Date: 3rd of March, 2023.


## There were 3 bugs in this project which I found out:

1. The 'ComingSoon' component was had a typo regarding the capitalization of the letters and it wasn't exported as default.

2. The Countdown timer went backwards even after passing 0, which resulted it to become negative. 

3. The form validation method to validate the email was faulty. 

## The 3 bugs were fixed by:

1. Fixing the typing mistake for the 'ComingSoon' component and making the function a default export.

2. Fixed the issue with the countdown timer by adding a logic to make the timer stop at 0 if the remaing time goes to negative. 

3. Fixed the logic in the form validation method. 




## Available Scripts

Download the project and then enter `npm i` to install all the dependencies.

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
