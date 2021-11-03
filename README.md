# Note taking app

&nbsp;
## Background

After your success with the weather widget, you have begun to make a name for yourself as a JavaScript expert in the office. One of the junior developers on your team cornered you in the breakroom to ask for help on an app he is making for practice.

The junior developer tells you he's made a front-end only note-taking app. He's not familiar with server-side technology yet, so he was hoping to be able to save the note content to the browser's storage instead. He asks you for guidance on how to do so.

When he shows you the app he's made, you realize he's very close to achieving this goal, and you decide to finish the app to teach him about `localstorage` and `cookies`.

&nbsp;
## Setup

Please create a git repository titled `m7-hw10-lastname-firstname` and clone the repo to your computer. Copy the files from the `unsolved` folder into your repository and ensure that `index.html` is in the root directory.

&nbsp;
## Instructions

Your assignment is to finish the note-taking application included in the unsolved folder. You only need to modify `index.js` in the specified places to complete this assignment. Upon completion, the app should:

1. Allow the user to type a custom name into the title of the app, and save that name in a cookie when the save button is clicked.
1. When refreshing the app, the name stored in the cookie is retrieved and populates the title.
1. Allow the user to type a note into the note area, and save that note content to localstorage when the save button is clicked.
1. When refreshing the app, the note content is retrieved from localstorage and populates the note area.
1. When the clear button is clicked, the content in the note area is cleared, and the note in localstorage is cleared as well.

&nbsp;
## Deployment

Your code must be deployed to GitHub Pages. To deploy a repository to GitHub pages you must

1. Ensure your repository has an `index.html` file in the root directory.
1. Navigate to the `settings` section of the repository.
1. Click on `pages` in the left navigation menu.
1. Under `source` click the dropdown and select your `master` or `main` branch.
1. Click `save`.

Your site should be deployed to `<your github username>.github.io/<your repository name>` in 5-10 minutes.

&nbsp;
## Submission

Please submit both a link to your repository and a link to the live site. Also please include any comments on stumbling blocks or difficulties encountered while completing the assignment.

&nbsp;
## Resources

This assignment will test your ability to work with client-side storage APIs in JavaScript.

- [localstorage on MDN](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
- [document.cookie on MDN](https://developer.mozilla.org/en-US/docs/Web/API/Document/cookie)
- [Cookies on W3 schools](https://www.w3schools.com/js/js_cookies.asp)