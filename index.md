## Welcome to the Kollektor GitHub Page

Kollektor is the final year project submission by Seamus McCarthy in the WIT Higher Diploma in Science in Computer Science 2020-2022.

Kollektor is a full stack MERN web application for users to catalogue & discuss their musical equipment collections.

### Project links

[Backend repository](https://github.com/SeamusMcCarthy/Kollektor-backend)

[Frontend repository](https://github.com/SeamusMcCarthy/Kollektor-frontend)

[Trello board for sprint management](https://trello.com/b/692Rurvy/agile-sprint-board)

[Main site](https://kollektor1-21c76.web.app)

[Project demo video](https://youtu.be/RU0VzdzBeeM)

### Automated testing
The bulk of the automated testing was performed using [Cypress](http://www.cypress.io). A recording of the tests in action can be found [here](https://youtu.be/upHu6RIM3I0)

Some preliminary automated testing was also performed using [Playwright.dev](https://playwright.dev/)

### Accessibility testing
As part of the automated testing, accessibility (a11y) checks were performed on the logged out pages. This was performed using the [cypress-axe](https://www.npmjs.com/package/cypress-axe) plugin and also using the [Axe DevTools](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd) Chrome extension.

### Images of site
Landing page when logged in
![Logged in page](/docs/assets/images/CatLoggedInPage.png)

Example of a typical entry
![Example of an entry](/docs/assets/images/EntryDetails.png)

Cypress tests in action
![Cypress tests](/docs/assets/images/CypressTest.png)

Using Axe DevTools Chrome extension to check for a11y errors
![Axe checks in browser](/docs/assets/images/AxeChecks.png)
