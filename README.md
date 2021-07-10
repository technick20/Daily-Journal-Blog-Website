# Daily-Journal-Blog-Website

This is a website where people can write their daily blogs and post them immediately.
This implemented using Node.js , Express and Database used is MongoDB


https://user-images.githubusercontent.com/64360913/125177132-014e1c00-e1f7-11eb-973b-31e895ec11b9.mp4



## Features

| Functions              | Detail                                            | URL                         |
| :--------------------: | ------------------------------------------------- | --------------------------- |
| Home Page | 1. User can see all the published posts on home page .<br>2. User can also compose new post by clicking at the '+' button at the end of page| / |
| Compose | 1. User can compose a new Post with title and content <br>2. User can see the posts published immediately on the home page |/compose |
| Read more | This function allows to read the full post with the post title on a new page |/postTitle |
| About Page | Shows the About page of the blog website |/about |
| Contact Page | Contact Page for the blog website |/contact |

### Prerequisites

- [Node.js v14.16.0](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/get-npm)
- [MongoDB shell version v4.4.6](https://www.mongodb.com/)

## Installation:
* Fork/clone this project to your local machine.
* Go to the location where project is downloaded in your terminal.
* Download all the dependencies.
```bash
> npm install
```
* Create blogDB by running app.js in mongo shell and using mongoose.
* Start the by running app.js.
```bash
> node app.js
or
>nodemon app.js
```
* Run your project on localhost:3000
