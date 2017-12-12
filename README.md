# CSC583-Final

Develope a `sign-in` application which runs on mobile devices, e.g. iPad, Android tablets, which will be used to collect information from visitors to a corporation. Application also provide admin view to
available data in database.

# Non-functional requirements

This application utilizes Vue.js, Node.js, &amp; MongoDB technologies. We have performed a detailed analysis and used this stack for our CSC583 class. As I am little familiar with this stack, I chose it to
develope this project

# Architecture
| VueJS |	Front end |
| :----- | :--------- |
| **NodeJS** |	**Web server** |
| **ExpressJS**	| **API** |
| **MongoDB**	| **Databse** |

# Plan of action

- [x] Analysis of non-functional requirements
- [x] Installation of stack
- [x] Implementation
- [ ] Testing

# Installation

Clone the repo to your local machne.

`git clone https://github.com/NickVispute/CSC583-Final.git`

Change your directory to project folder

`cd loginApp`

Install packages

`npm install`

Run mongoDB as service

`sudo service mongod start`

Run back-end

`node server`

Run front-end

`npm run dev`

App will open at http://localhost:3000 in browser.
