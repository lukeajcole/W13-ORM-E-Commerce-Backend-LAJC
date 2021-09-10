
# <ins>Employee Tracker</ins>
![](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
## Description

This is a simple backend that could be used for an ecommerce website. With the right front end skills, you could use this backend to create a site that allows users to create an inventory list that is complete with categories and tags.

## <ins>Table of Contents</ins>
- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)

## <ins>Installation</ins>

Before this backend can be used, be sure to fill out the .env.EXAMPLE file with your database information. Next, you will also need to make a clean database called "ecommerce_db"

with the database create run the following code in the command line from the ame directory as "server" in order to seed the database
 ```md
node seeds/index.js
 ```

Be sure to run the following command in a terminal that's opened in the same directory as server.js:
 ```md
 npm install
 ```
Finally, you can run the following code to run the backend and see it in action in an app like insomnia

 ```md
node server.js
 ```
## <ins>Usage</ins>

Below are some GIFs showing each of the available REST verbs in action for product, category, and tag. 

Set-up and GET ALL (Read) https://drive.google.com/file/d/1O2ZzdJ26YmB3RQs6wZOaApvnFrzKSAdW/view

![set-up](demo/set-up_get_All.gif)

POST (Create) and Get by ID https://drive.google.com/file/d/1Ve6Uq-6EVfg0Kl7zb2vTtherIMHxobQ0/view

![Post](demo/POST_GetByID.gif)

PUT (Update)  https://drive.google.com/file/d/1qtTFtPK56JTs_peR4ATvHmS1vPuHY7_N/view

![Put](demo/Put.gif)

DELETE (Delete) https://drive.google.com/file/d/1nuS8bkjLIfK4ms6hWmzy8hq9uwP413_z/view

![Delete](demo/delete.gif)


## <ins>Questions</ins>
Contact the creator of this E-Commerce Backend at lukeajcole@gmail.com. Github link: https://github.com/lukeajcole


