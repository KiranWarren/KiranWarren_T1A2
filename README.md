# Term 1 - Assignment 2 - Portfolio

### Kiran Warren

## Link to published portfolio website:

[Kiran Warren Portfolio](https://kiran-warren-portfolio.netlify.app)

## Link to Github repository:

[KiranWarren_T1A2](https://github.com/KiranWarren/KiranWarren_T1A2)

## Link to presentation video:

[KiranWarren T1A2 Presentation](https://youtu.be/sgFK6YauYKo)

## Description of portfolio website:

1.  Purpose

The purpose of my portfolio website is to share my professional capabilities/experience and my
personal interests with potential employers or clients.

The website will showcase my skills and experience through displayed projects, listed proficiencies, my resume, and the appearance and functionality of the website itself. The website should give
potential employers and clients confidence that I will be able to work for them efficiently and
effectively.

Being able to grab the visitor’s attention and stand out from the competition are important factors to consider. This is why I decided to go a more maximalist approach to the design and utilise a loud
aesthetic. The cyberpunk theme aesthetic is a reflection of what I personally enjoy and also is sure to grab the
attention of visitors.

2. Functionality/Features

- Pages:

  **Home** – The home page is a simple landing page with my name, a small welcome and navigation buttons as the centrepiece. The name in large font in the centre of the page was given a glitch effect using a keyframe animation that utilised text shadow effects in order to grab the visitor’s attention.

  The page elements have been positioned using flex display. This effortlessly keeps the centrepiece at the middle of the screen, the footer at the bottom of the page, and the KW logo in the top-left corner.

  **About** - The about page contains some personal information about myself, including career, family and hobbies. Each subject has a picture and a short description. The about elements have been positioned on the page using flex display and flex wrapping.

  **Portfolio** - The portfolio page contains three main sections.

  The top section contains a button that will open a pdf version of my resume. This is achieved by given the anchor tag a target attribute equal to \_blank.

  The second section contains a list of language and framework competencies. When hovered, the logos will slightly enlarge and shake. This was achieved by given the logos a hover pseudo selector that gave them a keyframe animation that utilised scale and translate transforms.

  The third section is a showcase of a diverse range of developer projects completed. Each project is displayed on a card, with a related picture, a small blurb, and buttons linking to a Github repository containing the project and a live demonstration of the project. Project cards are positioned on the page using flex display and flex wrapping. When hovering over a card, the card will increase in size by 33% to give the user a clearer focus on what they want to inspect.

  **Blog** - The blog page contains a list of blog entries displayed on cards. The cards contain the blog title, a related picture, blog topic, published date, a summary of the content, and a read more button. The blog cards are positioned on the page using flex display and flex wrapping. When hovering over a blog card, the card will increase in size by 33% to give the user a clearer focus on the blog entry. The read more button will take the user to page containing the full blog entry.

  **Contact** - The contact page contains two features.

  The feature on the left of the page is a box containing my contact information. A map of my general location is shown, however, this would preferably be a Google Map Embed API.

  The feature on the right of the page is a "contact me" box containing a form that allows the user to send me a message via email. Not currently functioning, requires a php script to process the information passed from the form.

- Aesthetic: The colour scheme and style chosen for all pages is a cyberpunk aesthetic. This features a static background image of a nighttime cityscape with neon pink and blues. The colour scheme chosen for the page follows the same style, using grey and dark grey as the main colours and bright pink and blue as accenting colours. This is an aesthetic that I personally enjoy and feel that it reflects the playfulness of my personality.

  All text is a dark colour, presented on a lighter colour, ensuring easy readability for the user. Borders of features glow with accent colours when hovered over with the mouse, to give character to the page and show focus on the element.

- Responsivenes: The website was designed with a desktop-first approach. I found it easier to envisage the site on a desktop as opposed to a mobile phone. To allow the page to display properly for mobile or tablet user, three media query breakpoints were added.

  The webpage displays as intended for screen widths larger than 1000px.

  The next size down was for medium sized screen (600px to 1000px). This breakpoint removed the scale transform from project and blog cards so that they didn't go off screen. It also changed the flex direction of webpage features (e.g. project cards) to column.

  The next breakpoint is for screens sized between 400px and 600px. The skills logos are changed from a row flex direction to a column direction to fit the screen more comfortably. The width of all features is given a maximum of 480px while in this screen range.

  The last breakpoint is for screens with a width below 400px. The max width of features is removed at this level, and is based on the width of the screen only.

- Accessibility: The use of semantic elements was used throughout the code. This will help other developers a much clearer idea of how the code is structured. It will also aid users who are using screenreaders understand the purpose of each element.

  The text used throughout the website is black on a light grey background (excepting the animated centrepiece on the home page). This will ensure good readability of the text throughout the website.

- Navigation: A navbar with all second level pages has been provided on all pages. All pages (except for home page) display a consistent navbar within the header. The KW logo in the header will also take the user back to the home page. The navigation buttons have a neon glow effect when hovered with the cursor.

  The home page has the navigation buttons brought to the centre of the screen as this page was designed to draw the users attention to the centre.

  The footer on all pages gives the user links to my Github account and LinkedIn account by clicking on the respective logos. The logos display a shake effect when hovered on with a mouse.

3. Sitemap

![Sitemap](/docs/sitemap.png)

4. Screenshots

Below are the final wireframes that were used to plan out the html elements and position them using css/scss.

**Home Page**
![Home Page Wireframe](/docs/home-page-wireframe.png)

**About Page**
![About Page Wireframe](/docs/about-page-wireframe.png)

**Portfolio Page**
![Portfolio Page Wireframe](/docs/portfolio-page-wireframe.png)

**Blog Page**
![Blog List Page Wireframe](/docs/blog-page-wireframe.png)

**Blog Post**
![Blog Post Page Wireframe](/docs/blog-post-page-wireframe.png)

**Contact Page**
![Contact Page Wireframe](/docs/contact-page-wireframe.png)

5. Target Audience

The target audience for my portfolio will be potential employers and clients.

The more colourful and playful presentation of my portfolio should be appreciated by employers that are looking for creative professionals.

The project list shows a diverse range of interests and skills which should be appreciated by employers that are looking for versatile and broadly-skilled professionals.

6. Tech Stack

- Website wireframes were created using Balsamiq Wireframes.
- VSCode was utilised to code the website, using HTML and CSS.
- The style sheet was written in SCSS using a Live SASS Compiler that compiled the style sheet to CSS.
- The project was pushed to a Github repository.
- The website was published to the internet using Netlify.
- The presentation was recorded using a screen recorder Chrome extension called "Scre.io".
- The presentation .webm file was uploaded to Youtube.com as an unlisted video.

### References

Images used in the project that were retrieved from the internet:

- _retro-future-bg.jpg_, image, PXFuel, viewed 2 June 2023, <https://www.pxfuel.com/en/desktop-wallpaper-iayeu >.

- _github-logo.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/github-logo_25231 >.

- _kw-logo-solid.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/kw_10041034 >.

- _kw-logo.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/kw_10041027 >.

- _linkedin-logo.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/linkedin_3536569?term=linked+in&amp;page=1&amp;position=2&amp;origin=search&amp;related_id=3536569 >.

- _html5-logo.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/html-5_174854 >.

- _css3-logo.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/css-3_732190 >.

- _js-logo.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/js_5968292 >.

- _sass-logo.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/sass_5968358 >.

- _python-logo.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/python_5968350 >.

- _react-logo.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/react_919851 >.

- _postgre-logo.png_, image, Flaticon, viewed 2 June 2023, <https://www.flaticon.com/free-icon/postgre_5968342 >.

- _drumkit-project.png_, image, Vecteezy, viewed 2 June 2023, <https://www.vecteezy.com/vector-art/15391577-drum-set-icon-cartoon-style >.

- _weather-project.png_, image, Freepik, viewed 2 June 2023, <https://www.vecteezy.com/vector-art/15391577-drum-set-icon-cartoon-style >.

- _8ball-project.png_, image, Harvey Norman, viewed 2 June 2023, <https://www.harveynorman.com.au/mattel-magic-8-ball-fortune-telling-fun-ma30188.html >.

- _survey-project.png_, image, Canva, viewed 2 June 2023, <https://www.canva.com/templates/s/survey/ >.

- _car-share-project.png_, image, Vox, viewed 2 June 2023, <https://www.vox.com/2016/7/28/12294214/shared-vehicles-livable-cities >.

- _parallax-project.png_, image, Unsplash, viewed 2 June 2023, <https://unsplash.com/s/photos/beautiful-landscape >.

- _colors.png_, image, Wikipedia, viewed 2 June 2023, <https://en.wikipedia.org/wiki/Paint#/media/File:Multicolored_tempera_paints.jpg >.

- _map.png_, image, Google Maps, viewed 2 June 2023, <https://www.google.com/maps >.
