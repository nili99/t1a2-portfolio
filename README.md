# T1A2: Portfolio - Nina Liang

## Documentation requirements

### A link to your GitHub repo

### Description of your portfolio website, including:

- Purpose  
- Functionality / features  
- Screenshots  
- Sitemap  
- Target audience  
- Tech stack (e.g. html, css, deployment platform, etc)

---

## R5 - Documentation must include an overview/sitemap of all the pages in your website. You must explain the overall structure of your website and how different pages will be navigated.

![Sitemap diagram](README-images/sitemap.png)

The structure of my website will have the **Home** page be primarily used to explain and navigate to 3 other pages. As seen in the sitemap diagram, these 3 pages are **About Me**, **Blog** and **Contact**.  

All pages will have a navbar at the top with the options **Home**, **About Me**, **Blog** and **Contact** as well as a section containing larger buttons at the end of the page for ease of navigation.

The **Blog** page will link to individual **Blog Article** pages and is intended to be an index list of all the published blog articles. Every **Blog Article** page will additionally have buttons to navigate to the previous article, back to the **Blog** list page and the next article.

---

## R6 - Documentation must include wireframes or mockups of the pages of your website. You must explain your decision making process relating to the overall aesthetic of your website.

### Overall Aesthetics and General Layout

**Colours:** Pastel colours were chosen for each page to help differentiate each topic, provide soft contrast with each other and improve accessibility. Colour coordinating the pages to different topics is helpful for accessibility as the user can more easily identify where they are and more confidently navigate around the website.  

**Mobile-First and Responsive Design:** Mobile-first design was used to create a responsive and accessible layout for the website. This strategy helps to make the website adaptable to different screen sizes so that the content can still be read properly. Flexbox allows the content boxes to be automatically placed in a column on screens that are narrow or placed in a row on screens that are wider. This improves the readability of the content for multiple sizes as the mobile layout would be less pleasant to users on desktop browsers.

**Navigation:** The website has a small navbar at the top to navigate to the 4 core pages. Additional sections have been added to the bottom of each page to provide more accessible navigation. These sections are also intended to be used to assist the flow of the content so that users have easy access to every section of the website. The navigation sections are also designed to stand out with their size but still fit in aesthetically with their colour schemes.

**Layout:** Each page follows the same layout from top to bottom: navbar, header, content, navigation section, footer. This is so the information is consistent across all pages and users can more easily navigate. This layout puts more emphasis on the content of each page, which is usually how mobile-first design is implemented.

### Screenshots and Differences of Each Wireframe

***Home Page*** ![Home page wireframe](README-images/wireframe-home.png)
The **Home** page main content section will consist of 3 blocks containing the title and description of each page. These blocks will use flexbox to achieve the layout in the wireframe.

***About Me*** ![About Me page wireframe](README-images/wireframe-about-me.png) 
The **About Me** page will include information about my name, personal interests, work and/or study history. A link to my resume will also be included at the bottom of the content section.

***Blog List*** ![Blog page wireframe](README-images/wireframe-blog.png)
The **Blog** page will have a preview of each blog article that includes the title, description, date published and image. They will be ordered from newest to oldest in rows where applicable.

***Blog Articles*** ![Blog Article pages wireframe](README-images/wireframe-blog-posts.png)
The **Blog Article** pages will include a photo, title and the content of the article. Underneath each article will be navigation buttons that lead to the previous article, the blog list, and the next article.

***Contact Me*** ![Contact page wireframe](README-images/wireframe-contact.png)
The **Contact Me** page will include links to my LinkedIn, Github, and Twitter accounts.

---

## R7 - Documentation must include a list of components that will be used. You must explain how components and styling will engage the audience.
Components I am using will be listed below:
- nav for Navbar
- header for Header or Jumbotron
- main for content between Header and Footer
- section for the different sections inside the main content
- div for the different areas and buttons inside the sections 
- footer for the footer bar at the bottom of the page

Styling will be used to help colour the website with my 4 key colour codes for each area of the website. I will apply fonts, center elements, round edges and adjust them accordingly for aesthetic purposes. I will also use media queries to determine the width and height of each element within the main content area.