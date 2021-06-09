### Context 📚

<!--
    Add your related (JIRA/Issue Tracker) tickets here.
    If you don't have an associated ticket, just write _Unticketed_.
-->

[PROJ-100](https://mycompany.atlassian.net/secure/RapidBoard.jspa?rapidView=104&projectKey=PROJ&view=planning&selectedIssue=PROJ-100), [PROJ-101](https://mycompany.atlassian.net/secure/RapidBoard.jspa?rapidView=104&projectKey=PROJ&view=planning&selectedIssue=PROJ-100)


### If merged, what value will this MR add to the codebase? ⭐️ 

<!--
    Please tell me why am I looking at your code.
    What should I be concerned about, while reviewing. 
-->

In a nutshell, this PR adds 2 major features to our core entity classes. I've also updated the unit tests to reflect the new changes and remove some legacy unit tests that no longer make sense after this change.

Unfortunately, this change as visual repercurssions, please see the design changes below.

### Design Changes 🏞

![design change](https://res.cloudinary.com/practicaldev/image/fetch/s--Nrzp31zz--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/kml9j34p9taplrnqtcez.jpg)

<!--
    Are there design changes involved?
    Are you pushing changes that add nice unit test reports to our terminal?
    Are you pushing nice cucumber reports?

    If YES to any of the above, please share and show us one or more screenshots.
    No? Then go ahead, and delete this section please.
-->

### Checklist:

- [ ] Make sure you are making a pull request against the dev branch (left side). 
Also you should start your branch off our dev.
- [ ] Check the commit's or even all commits' message styles matches our [requested structure](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716).
- [ ] Check that your code additions will not fail either code linting checks or unit tests.

💔 Thank you!