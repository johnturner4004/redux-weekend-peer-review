Hey Eyram,

First note I want to make is I like the welcome page. I don't think this was one of the requirements which is why I gave it a shoutout because it does make the app feel more inviting.

---
| Functional Requirements | Complete? |
| --- | :---: |
| Multi page form with client side routing and navigation (next button) | yes |
| Data stored in Redux when navigating from page to page |yes |
| User is notified when trying to leave a blank score | yes |
| Review Component displays scores and comments from current redux state | yes |
| Submit button sends data to the server via Axios | no |
| Confirmaion Page displays after data is POSTed to the server | no |
| Button on Confirmation Page clears Redux and starts a new survey | yes |
| Views are broken down into components | yes |

---
### Notes:

You did validate that input fields and that they were between 1-5. There is an imput parameter you can use to set a max and min value that limits what someone can get with the up and down arrows if you want. This wasn't a requirement so I'm more throwing it out as an FYI. It doesn't look like information is getting sent to the server and there is an alert when the Submit button is clicked.

---
| General Items | Complete? |
| --- | :---: |
| More than 15 git commits | yes |
| Commits are descriptive of the changes made or feature added | yes |
| Readme file updated | no |
| Appropriate amount of code comments | no |
| Code is consistently formatted | yes |
| Server code organized with router & module files | no |

---
### Notes:

Overall looks great. I see some comments in your commits about your POST route but don't see any routes in your server.js file and there isn't a router file or code so check to see if maybe you missed entering a
```
git add .
```
somewhere.
