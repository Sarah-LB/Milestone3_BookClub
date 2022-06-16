<h1 align="center">Book Club</h1>

[View the live project here.]()

This is a book review amd recommendation site. It is designed to be responsive and accessible on a range of devices, making it easy to navigate for potential users. Users can find inspiration for their next read by searching for books included in the Amazon database.  They can then add their own comments for those books to the Book Club database and rate it for future users' information.

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find recommended books to read.
        3. As a First Time Visitor, I want to locate social media links to see their followings on social media.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to be able to easily find the book I have read and add my own comments and ratings to the database.
        2. As a Returning Visitor, I want to find community links.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to be able to easily locate my reviews in order to edit or remove these from the database.

    -   #### Developer/Site Owner Goals

        1. As the Site Owner, I want to provide a book recommendations site where I can earn money on each book purchased via a link from the site.


-   ### Design
    -   #### Colour Scheme
        -   The two main colours used are Amber and Indigo.  Amber is a warm and friendly colour, stimulating creativity.  This is balanced by the calmer and more intellectual feel of indigo.
    -   #### Typography
        -   The Indie Flower font is used for the main headings on eavh page of the site.  It is a friendly cursive font that embodies the relaxed nature of the Book Club.
    -   #### Imagery
        -   It was important to keep imagery to a minimum to draw the users' focus to the book cover images.  Font awesome has been used throughout the site to make it easier to use/navigate.

*   ### Wireframes

    -   [Home page - logged out](static/images/Home%20(before%20logging%20in).png)
    -   [Home page - logged in](static/images/Home%20(logged%20in).png)
    -   [Book Review Template](static/images/Book%20review%20template%20(logged%20in).png)
    -   [Edit Review](static/images/Edit%20book%20review%20and%20add%20comment_rating%20(logged%20in).png)
    -   [Find A Book](static/images/Find%20a%20Book%20(logged%20in).png)
    -   [Login](static/images/Log%20In%20(before%20logging%20in).png)
    -   [Profile](static/images/Profile%20(logged%20in).png)
    -   [Register](static/images/Register%20(before%20logging%20in).png)
    -   [Submit a review 1](static/images/Submit%20a%20review%20page%201%20(logged%20in).png)
    -   [Submit a review 2](static/images/Submit%20a%20review%20page%202%20(logged%20in).png)

## Features

-   Responsive on all device sizes

-   Interactive elements

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [JavaScript](https://www.javascript.com/)
-   [Python]https://www.python.org/)

### Frameworks, Libraries & Programs Used

1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Indie Flower' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Materialize to make the navbar responsive but was also used for other functions in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the  during the design process.
1. [Flask](https://flask.palletsprojects.com/en/2.1.x/)
1. [MongoDB](https://www.mongodb.com/)
1. [Materialise:](https://materializecss.com/)
1. [Werkzeug:](https://werkzeug.palletsprojects.com/en/2.1.x/) for security features. hashing passwords to add security

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results]()
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results]()

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site.

        1.  The headings on the site are clear and the opening paragraph explains the site's purpose.

    2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find recommended books to read.

        2. The navbar is clear and easy to navigate.
    
    3. As a First Time Visitor, I want to locate social media links to see their followings on social media.

        3.  The social media links are listed in the footer on every page.

-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to be able to easily find the book I have read and add my own comments and ratings to the database.

        1.  There is a search function clearly displayed at the top of the find a book page and pages have been given clear names based on what they do.

    2. As a Returning Visitor, I want to find community links.

        2.  There are social media links in footer of every page.

-   #### Frequent User Goals

    1. As a Frequent User, I want to be able to easily locate my reviews in order to edit or remove these from the database.

        1.  On the profile page, users can find only their reviews with an option to edir or remove.

-   #### Developer/Site Owner Goals

    1. As the Site Owner, I want to provide a book recommendations site where I can earn money on each book purchased via a link from the site.

        1.  This has not been accomplished.  An affiliate link will be added to each review.html page.

### Further Testing

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   On some mobile devices the Hero Image pushes the size of screen out more than any of the other content on the page.
    -   A white gap can be seen to the right of the footer and navigation bar as a result.
-   On Microsoft Edge and Internet Explorer Browsers, all links in Navbar are pushed upwards when hovering over them.

## Deployment

### Heroku

The project was deployed to Heroku using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Log in to [Heroku](https://heroku.com/) and create your app.
3. Link your heroku app to your github repo.
4. Allow automatic deployment to GitHub.


### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

-    [Materialise:](https://materializecss.com/): Materialize Library used throughout the project.

-   The Code Institute study material was used heavily for inspiration, especially the mini project amd sample README.

-   [Rate Yo](https://rateyo.fundoocode.ninja/) was used for the star ratings.


### Content

-   All initial content was written by the developer but content will also be added by users.

-   Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

-   Images are added to the database by users.

### Acknowledgements

-   Tutor support at Code Institute for their support and advice.