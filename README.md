# Frontend Development Test

## Task: hCard Builder

### Features:
* As the form is filled using the left pane, preview is automatically updated.(using jQuery)
* Earlier used a dedicated function for every 'keyup' action on the fields, later on create a function 'updateContent', so that same stuff is not repeated and the funciton is reused for every action (using Event Delegation)
* 'Create hCard' button does not perform any action as it does not have a backend.
* 'Update Avatar' button updates the thumbnail image in the right preview pane.
** Assumption: when a user click this button, the preview thumbnail changes from a male thumbnail to a female thumbnail and vice versa.
* The form is responsive with different screen widths, i.e. Large screens, medium screens, small screens and mobile screens(using BootStrap)
* The form is  compatible across browsers.
* For simplicity, CSS is used. Can use SASS as well


### Duration:
Spent ~4 hours(Nov 30) + 0.5 hours(Dec 6) as was waiting for a clarification from Hollie.

### Accessible at:
The form is uploaded at gh-pages as well, in order to test the responsiveness.
Click [here](https://triptiwani.github.io/DhCard/index.html) to access it.

=========================================================
# Frontend Development Test

## Task: hCard Builder

[hCard is a simple, open format for publishing people, companies and
organizations on the web](http://microformats.org/wiki/hCard).

Our ever-vigilant design/UX team has put together a layout for an app, *hCard
Builder*. This app is something we would like to use in the future when allowing
users to edit their personal details on our site.

Based on the design provided (in `design.psd`), build the *hCard Builder* app in
HTML/CSS/JS, as if it was going to be shipped live at the end of the next sprint
once fully verified working by the testing team.

(**Note:** If you don't have Photoshop available, you can see examples of the
empty & completed states in the two provided `.png` files)

Allow approximately 4-5 hours to complete the task.

### Requirements

* As the form is filled out, the preview should be automatically updated
* The submit button does not need to function (ie; no backend is required for
  this task)
* When the user selects an image, a thumbnail should be shown in the preview
  (no backend is required for this task)
* The app should be responsive for different screen widths
* The form should work in the following browsers:
  * Internet Explorer 10+
  * Latest Chrome
  * Latest Firefox

(**Note:** For oldIE, the form does not have to look identical to more modern
browsers, but should be a reasonable approximation, and should still be
functional. Where required features are unavailable, the app should gracefully
degrade.)

### Guidelines

* We are interested in your coding style and how you solve problems. To this
  end, please include your source code and any build steps / explanations we may
  need to test the submission
* Please make sure your HTML is valid
* Please structure the code for reusability
* Where possible, keep SEO in mind
* Feel free to use any frameworks or preprocessors you are familiar with

### Submission

Please submit a *complete* copy of the source code you wrote for this test.

Upon submission, please also give us a guide to how long you spent on the test
(There is no wrong answer! We iterate on this test based on the average time
taken so we can provide an accurate time-frame for future candidates).

Submission can be in any format where we have access to the required files
(`.zip`, GitHub, carrier pigeon, etc - your call!)
