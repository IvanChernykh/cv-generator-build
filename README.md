# Resume Builder

The Resume builder is made for creating resumes. Implemented without backend. Instead I decided to use json file as a configuration file. So if you want to edit your resume later, you need to download it as a json file and then upload this file into the app to continue editing.

## Problems

In pdf, by default, links don't open in a new tab.

Application doesn't work properly on mobile devices because I used the react-pdf-renderer library to render PDF and it doesn't allow rendering pdf on mobile by default, unfortunately I noticed it only after I created the whole app. Due to my laziness, I decided not to fix this issue and not implement responsivness.
