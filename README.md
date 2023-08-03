# Blog-Website
Blog Website using EJS with Express

1) Clone Project to Code Editor
2) Run -npm install- in terminal
3) Run -nodemon app.js - in terminal
4) Run http://localhost:3000/ - on web browser to have website running.

This is a Blog Website Challenge Presented by Angela Yu's Udemy Online Web-Development Course. The purpose of this project is to display the use of Embedded JavaScript templating with Express and to demonstrate the power of creating multiple pages with a single EJS Template.
Once you have cloned this project into your preferred Code Editor, you must run npm install in order to install the project dependencies. Once you have installed the packages, you can then run nodemon app.js to have the project up and running on your localhost ie - http://localhost:3000/.
The project consists of 5 pages. The first page is the home page, the second page is the about page, and the third page is the contact us page. If you go the compose page by entering in the following http://localhost:3000/compose, you will be directed to the Compose Page. This is the fourth page.
At the compose page, you will be able to create your preferred Blog Post with an unique Title & Content. Once you have clicked publish , you will be redirected to the home page. You will see that the home page now has your Blog with the Title & Content.  You will notice on the Home Page where your blog post has been posted, there is a Read Me link beside it.
This Read Me link when clicked on will take you to its individual Blog Page - where you can see the full content. At the Home Page the Blog Content is limited to 100 Characters. The individual Blog Page will have the  following link -http://localhost:3000/posts/:postTitle. This is the fifth page. The :postTitle is used as an example here it will be any title you created from your Blog Post.
This :postTitle in the link is related to the very Title you created on your compose page and displayed on the Home Page. As you will see you can make multiple Post Requests on the compose page. These Blogs will all be displayed on the Home Page and by clicking on these individual Blog Contents - Read Me Link -  on the Home Page, it will direct you to their individual blog pages.
The individual blog pages are completed through the use of EJS templating, without having to create multiple EJS pages, we are able to use a single Template for the individual blog pages.

