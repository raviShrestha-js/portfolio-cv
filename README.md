# portfolio-cv

# My FrontEnd Developer Portfolio Website

This is my resposive portfolio website which I have created to showcase about me, my skills, experience and projects to the potential recruiters. Users can email me, call me, see my location and also submit their interest via the form submission in the contact me section. There is a download CV button which the users can click to download my CV in pdf format.

## UX

My website is for potential recruiters / hiring managers, who are looking to recruit a skilled frontend developer. I have included links and button to navigate through the website as well as github links and live preview links to all my working projects I have done till today. The Navigation bar follows along all the page with the users to give a easy navigation in the webpage.

I've chosen to style my website in the way that would give a refreshing icy cool feeling to the users and some nepalese touch by adding some of My country Nepal's background. I feel proud of being a Nepalese Programmer and that is what I have illustrated in my portfolio as well.

### User Stories

-As a potential recruiter, I want to download the CV of the developer.
-As a potential recruiter, I want to hire the developer and send a message with a subject of interest.
-As a user, I want a easy navigation in the webpage and know ehich section I am recently viewing.
-As a potetial recruiter, I want to know the developer's skills, education and experience.
-As a potential recruiter, I want to see the code and live preview of the projects that the developer has worked on.
-As a potential recruiter, I want to know the location and contact the developer through different means.
-As a potential recruiter, I want to visit linkedin, github, instagram and facebook profile of the developer.
-As a developer, I want to recieve the message sent by the potential recruiter through the form submission.

### Wireframes

I have drawn the wireframes roughly in my notebook. As it is not clear and presentable, I have not included them in the github site.

## Features

### Existing Features

#### All Pages

- **'hireMe' and 'downloadCV' Buttons** - Clicking the 'hireMe' button users will redirected to the contact me section where they can submit their details and message. And 'downloadCV' button downloads the CV in the local storage of the user in Pdf format.
- **Hamburger button** - Clicking the hamburger button triggers a full screen overlay menu containing the navigation links to all sections on my website. The user can click the links to navigate to the relevant section.
- **Social media links** - Each link opens a new page with the relevant social media page of me (Facebook, Twitter and YouTube). These links make it easy for users to access my social media profiles from one place. The social media profiles load in a new tab, which allows users to then return to the site.
- \*\*\*\* -
- **Navigation links** - Allows users to navigate around my website by clicking each navigation link, which redirects them to the relevant webpage.

## Technologies Used

- [**Balsamiq**](https://balsamiq.com/)
  - I've used **Balsamiq** to create wireframes of my website before building the actual site.
- [**HTML5**](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
  - The project uses **HTML5** to create the basic elements and content of my website.
- [**CSS3**](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
  - The project uses **CSS3** to add custom styles to the elements and content of my website.
- [**Bootstrap v4.3**](https://getbootstrap.com/)
  - The project uses **Bootstrap v4.3** to add a responsive grid system, prebuilt components, plugins built on jQuery, and Bootstrap styles to my website, before adding my custom styles.
- [**JavaScript**](https://www.javascript.com/)
  - The project uses **JavaScript** from Bootstrap which is required to add functionality to some of Bootstrap's components.
- [**Google Fonts**](https://fonts.google.com/)
  - The project uses **Google Fonts** to style the text and suit the style of the band.
- [**Font Awesome**](https://fontawesome.com/)
  - The project uses **Font Awesome** for the social media links and contact icons on my website.
- [**Git**](https://git-scm.com/)
  - I've used **Git** as a version control system to regularly add and commit changes made to project in Cloud9, before pushing them to GitHub.
- [**GitHub**](https://github.com/)
  - I've used **GitHub** as a remote repository to push and store the committed changes to my project from Git. I've also used GitHub pages to deploy my website in a live environment.

## Testing

### Testing User Stories

I used my user stories and documented each of the steps that each user would need to accomplish what they have stated. Below is the link to the document that contains this information:

- [Testing User Stories](https://github.com/hebs87/monkees-milestone-project-one/blob/master/testing-documents/testing-user-stories.pdf)

### Responsive Testing

I used Google Chrome's Development tools to constantly test each change that I made to my website and to ensure that it appeared in the desired way on different screen sizes. I also tested my website on different screen sizes (mobile, tablet and desktop) to ensure it appeared in the desired way on different devices.

To test my whole website, I went through each page, feature by feature, and documented the results on a spreadsheet. The spreadsheet also documents any responsive features and confirms that they work and appear as intended on different screen sizes. The link to the spreadsheet it below:

- [Testing Checklist](https://github.com/hebs87/monkees-milestone-project-one/blob/master/testing-documents/testing-checklist.pdf)

### HTML and CSS Validation

I used the [W3C HTML Validator tool](https://validator.w3.org/#validate_by_input) to validate my HTML code.

I used the [W3C CSS Validator tool](https://jigsaw.w3.org/css-validator/#validate_by_input) to validate my CSS code.

### Interesting Bugs or Problems

- **Burger icon** - The burger icon wasn't appearing once the fullscreen overlay menu was triggered. The reason for this is that the header in which the burger icon was in had a lower z-index than the overlay menu. To fix the issue, I gave the header a higher z-index value than the overlay menu.
- **Burger icon when overlay menu is triggered** - As the header (including the burger icon) is part of the page, it disappears when the user scrolls down while the overlay menu is triggered. The user then has to scroll back to the top of the page for the burger icon to reappear while the overlay menu is triggered. This is another constraint, and I will fix this bug when I learn JavaScript, so that the header remains fixed, only when the overlay menu is triggered.
- **Band card images** - The images automatically take up 100% of the card width, so they appear stretched. I have tried to make the images take up less of the card width, but this throws the alignment out, and it doesn't look as tidy with the scroll bars. This is a constraint and I've decided to leave the images as they are.
- **'dates' attribute** - For the discography timeline, I used the sample code from the code used within the Resume mini project. The sample code used the `dates` attribute. However, the [W3C HTML Validator tool](https://validator.w3.org/#validate_by_input) stated that this was invalid. When I looked on Slack, I saw that another student had the same issue, and the advice they received was to use the `data-year` attribute instead. I tried this and it resolved the issue.
- **'Submit' button on _Book Us_ form** - Once I entered the information and submitted the form, the form kept routing me through to the index.html page. After speaking with my mentor, he asked me to check the value of the `action` attribute of the `<form>` element. The issue was that the value I was using was `action="/"`. Once I changed this to `action="contact.html"` the issue was resolved.
- **'Submit' button on _Book Us_ form** - Once I entered the information and submitted the form, I kept getting a '405 Not Allowed' error message, but this was only happening in the live environment and not the testing environment. I posted this in the Slack community and was given the advice to change the `method` value to `get` instead of `post`. This resolved the error.

## Deployment

The hosting platform that I've used for my project is GitHub Pages. To deploy my website to GitHub pages, I used the following steps:

1. Loaded the terminal window in my Cloud9 workspace.
2. Initialised Git using the `git init` command.
3. Added all files to the Staging area (Git) using the `git add .` command.
4. Committed the files to Git using the `git commit -m "Initial commit"` command.
5. Created a new repository in GitHub called 'monkees-milestone-project-one'.
6. Copied the below code from GitHub into the terminal window in my Cloud9 workspace:

   `git remote add origin https://github.com/hebs87/monkees-milestone-project-one.git`

   `git push -u origin master`

7. Entered my GitHub username and password to push the files from Git to GitHub.
8. Went into 'Settings' on my repository page in GitHub.
9. Selected the 'master branch' option under the 'GitHub Pages' section.
10. Ran several regular commits throughout my project.

### Repository Link

https://hebs87.github.io/monkees-milestone-project-one/

### Running Code Locally

To run my code locally, users can download a local copy of my code to their desktop by completing the following steps:

1. Go to [my GitHub repository](https://github.com/hebs87/monkees-milestone-project-one.git).
2. Click on 'Clone or download'.
3. Click on 'Download ZIP'.
4. Once dowloaded, extract the zip file's contents and run my website locally.

## Credits

### Content

- The text for Davy Jones' band card was copied from [Davy Jones' Wikipedia page](<https://en.wikipedia.org/wiki/Davy_Jones_(musician)>).
- The text for Micky Dolenz's band card was copied from [Micky Dolenz's Wikipedia page](https://en.wikipedia.org/wiki/Micky_Dolenz).
- The text for Michael Nesmith's band card was copied from [Michael Nesmith's Wikipedia page](https://en.wikipedia.org/wiki/Michael_Nesmith).
- The text for Peter Tork's band card was copied from [Peter Tork's Wikipedia page](https://en.wikipedia.org/wiki/Peter_Tork).
- The text for the 'Band History' section and the discography information was copied from [The Monkees' Wikipedia page](https://en.wikipedia.org/wiki/The_Monkees).

### Media

- The photos used in this site were obtained either from the assets provided with the course content, or from Google images. I made sure any Google images were "free to use or share, even commercially".
- The audio tracks used in this site were obtained from the assets provided with the course content.
- The video track used in this site was obtained from the assets provided with the course content.
- The link for the iframe content for the _'Monkeemania: The Very Best Of The Monkees'_ album was obtained from [the album's Spotify page](https://open.spotify.com/album/1mOeF3Ew1vdmJLbGOG2CuP).
- The link for the iframe content for the _'Monkees Greatest Hits'_ album was obtained from [the album's Spotify page](https://open.spotify.com/playlist/7mbzl6fkxbayOw7OwjDMHG).
- The follow button embed code was obtained from [the band's Spotify page](https://open.spotify.com/artist/320EPCSEezHt1rtbfwH6Ck).

### Acknowledgements

- I received inspiration for the full screen overlay menu when I was looking at websites for other bands. I came across the website for the band called [The Specials](https://www.thespecials.com/) and wanted to incorporate a similar menu in my project.
- I received inspiration for the spinning music discs from my fiancee. When she looked at my website, she suggested this as some sylistic feedback.
- Thanks to the Slack community to help me to fix an error with the `dates` attribute in the discography timeline, and to help me to fix the error with the Book Us form on the contacct.html page.
- A special mention to my mentor, Dick Vlaanderen, for his feedback on my project's scope and design, and for hints on what information to include in my README.md file to justify my stylistic choices.
