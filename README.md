# Reactfolio V1.2 👩🏽‍🚀

Reactfolio is a modern and customizable personal portfolio web template built using the popular React library. It provides an easy way for developers, designers, and creatives to showcase their work, skills, and achievements in a professiona and visually appealing way. With its responsive design and clean code, Reactfolio can be easily tailored to suit individual needs and preferences, making it an ideal choice for anyone looking to create a stunning online portfolio.

<center>
<img src="https://i.imgur.com/ZWPO61A.jpeg" alt="Reactfolio" />
</center>

Live demo here: <a href="https://vikramaditya-rho.vercel.app/" target="_blank">Vikramaditya.dev</a>

-   [Features](#-features)
<!-- -   [Getting started](#-getting-started)
-   [Installation and Setup Instructions](#-installation-and-setup-instructions)
-   [Folder structure](#-folder-structure)
-   [Configurations](#-configurations)
-   [Google Analytics](#-google-analytics)
-   [Building the React App](#-building-the-react-app)
-   [FAQ](#-faq)
-   [Contribution](#-contribution) -->

## 📙 Features

-   📖 Multi-Page Layout
    -   Home
    -   About
    -   Projects
    -   Articles
    -   Contact
-   📱 Fully Responsive
-   🛠 Easy configurations



## 🛠 Installation and Setup Instructions

1. Installation: `npm install`

2. Run the project: `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload if you make edits.

## 📁 Folder structure

-   `/public`: publicly accessible contents (ex: images, media).
-   `/src`: all the components used in this project.
    -   `/src/components/`: each reusable components of each pages.
    -   `/src/data`: configurations of the web app.
    -   `/src/pages`: pages that include in the web app.



<!-- -   `articles.js`

    From this you can add your articles to the web application.

    Instructions:

    -   Add new article

        1. Create a new function starts with `article_`. For example you can add new function named `article_3`.

        2. Then add the data accordingly.

            - Add `<React.Fragment>` tag and it's closing tags in body.
            - In React there has no keyword `class`, so you should use `className` to define html classes.

            ```js
            function article_3() {
            	return {
            		date: "7 May 2023",
            		title: "The Benefits of Cloud Computing",
            		description: "Why businesses are turning to the cloud.",
            		style: `
            				.random-image {
            					align-self: center;
            					outline: 2px solid red;
            				}
            				`,
            		body: (
            			<React.Fragment>
            				<div className="article-content">
            					<div className="paragraph">
            						Content of article 1
            					</div>
            					<img
            						src="https://picsum.photos/200/300"
            						alt="random"
            						className="random-image"
            					/>
            				</div>
            			</React.Fragment>
            		),
            	};
            }
            ``` -->

        3. In the last lines you will see an array to which you need to add your new `articles` function.

            ```js
            const myArticles = [article_1, article_2, article_3];
            ```

-   `seo.js`

    The SEO.js file is a module that contains an array of objects, with each object representing metadata for a specific page of a React website. The purpose of this file is to centralize and manage the SEO (Search Engine Optimization) information for different pages.

    Each object in the SEO array has the following properties:

    `page`: Represents the page name or identifier. It helps in mapping the SEO data to the appropriate page.

    `title`: Specifies the title of the page. This title is typically displayed in the browser's title bar and is an important element for search engines.

    `description`: Provides a concise and informative description of the page content. This description is often displayed in search engine results and can greatly influence click-through rates.
    keywords: Contains an array of keywords relevant to the page's content. Keywords can help search engines understand the topics covered on the page and can impact its visibility in search results.
    By storing the SEO information in the SEO.js file, you can easily manage and update the metadata for different pages of your React website. This approach allows you to keep the SEO data separate from the components and reuse it across the application, ensuring consistent and optimized metadata for each page.

    Example:

    ```js
    const SEO = [
    	{
    		page: "home",
    		description:
    			"I am a backend developer with expertise in Node.js. I have experience in building scalable, secure and reliable web applications using various frameworks and technologies.",
    		keywords: ["Tharindu", "Tharindu N", "Tharindu Nayanajith"],
    	},
    ];
    ```

-   `styles.css`

    From this you can change the font colors and font families of the web application.

    ```css
    :root {
    	/* ------- colors ------- */
    	--primary-color: #27272a;
    	--secondary-color: #65656d;
    	--tertiary-color: #acacb4;
    	--quaternary-color: #e4e4e7;
    	--link-color: #14b8a6;
    	/* ---------------------- */

    	/* ------- fonts ------- */
    	--primary-font: "Heebo", sans-serif;
    	--secondary-font: "Roboto", sans-serif;
    	/* --------------------- */
    }
    ```



## 🌱 Contribution

If you have any suggestions on what to improve in Reactfolio and would like to share them, feel free to leave an issue or fork project to implement your own ideas
