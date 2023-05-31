# Term 1 - Assignment 2 - Portfolio

### Kiran Warren

## Link to published portfolio website:

[Kiran Warren Portfolio](https://kiran-warren-portfolio.netlify.app)

## Link to Github repository:

[KiranWarren_T1A2](https://github.com/KiranWarren/KiranWarren_T1A2)

## Link to presentation video:

[]()

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

- Aesthetic - The colour scheme and style chosen for all pages is a cyberpunk aesthetic. This features a static background image of a nighttime cityscape with neon pink and blues. The colour scheme chosen for the page follows the same style, using grey and dark grey as the main colours and bright pink and blue as accenting colours. This is an aesthetic that I personally enjoy and feel that it reflects the playfulness of my personality.

  All text is a dark colour, presented on a lighter colour, ensuring easy readability for the user. Borders of features glow with accent colours when hovered over with the mouse, to give character to the page and show focus on the element.

- Responsiveness - The website was designed with a desktop-first approach. I found it easier to envisage the site on a desktop as opposed to a mobile phone. To allow the page to display properly for mobile or tablet user, three media query breakpoints were added.

  The webpage displays as intended for screen widths larger than 1000px.

  The next size down was for medium sized screen (600px to 1000px). This breakpoint removed the scale transform from project and blog cards so that they didn't go off screen. It also changed the flex direction of webpage features (e.g. project cards) to column.

  The next breakpoint is for screens sized between 400px and 600px. The skills logos are changed from a row flex direction to a column direction to fit the screen more comfortably. The width of all features is given a maximum of 480px while in this screen range.

  The last breakpoint is for screens with a width below 400px. The max width of features is removed at this level, and is based on the width of the screen only.

- Navigation - A navbar with all second level pages has been provided on all pages. All pages (except for home page) display a consistent navbar within the header. The KW logo in the header will also take the user back to the home page. The navigation buttons have a neon glow effect when hovered with the cursor.

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

### References

Images used in the project that were retrieved from the internet:
