## The ATM problem Rollet homework

### Short Description
Develop the note dispenser logic of an ATM.
Details

### User stories
- As a user I want to be able to enter the amount I want to withdraw from the ATM (I
always have enough money in my bank account)
- As a user I want to see what bills the ATM gives me - if able - once I entered and
submitted the desired amount
- As a user I want to see an error message if the ATM is unable to give the desired
amount due to the lack of appropriate bills
- As an operator I want to see the withdrawal history including time, success status and
amount as well as the remaining notes in the ATM
- As an operator I want to be able to see and manipulate the amount of each bill in the
ATM


### Extra Info
This ATM is only filled with the following notes: 20000, 10000, 5000, 2000 (note there is no
1000 bill)

### Frontend
Implement a frontend that is appropriate for the aforementioned user stories for both a user and
operator.
The withdrawal history and the state of the notes of the ATM should be kept up to date after
each action (withdrawal or note manipulation)

### Backend
Implement a REST API that provides endpoints for the withdrawals (history) and the current
state of notes in the ATM.
Also the backend should implement the logic that decides on what notes to give if able.

### Database

The database should store what bills the ATM has. The database of the notes should be kept up
to date at all times.

---

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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
