# QuestBoard

QuestBoard is a Node.js web application that allows users to create, edit, delete, and view posts. Each post is assigned a unique ID using the `uuid` library. This project uses Express.js for the backend and EJS for templating.

## Features

- View all posts
- Create a new post
- Edit an existing post
- Delete a post

## Technologies Used

- Node.js
- Express.js
- EJS
- UUID
- Method-Override

## Installation

## 1. Clone the repository:

   1. git clone https://github.com/roshnigithub5/questboard.git
   2. Navigate to the project directory: cd questboard

## 2. Install the dependencies:

  1. npm install
  2. Start the server: node index.js

## The application will be running on http://localhost:8500.

## Usage
View Posts: Navigate to http://localhost:8500/posts to see all posts.
Create Post: Go to http://localhost:8500/posts/new to create a new post.
Edit Post: Click the edit button on a post to edit its content.
Delete Post: Click the delete button on a post to remove it.

## Code Overview
index.js: The main server file where all routes and middleware are defined.
views/: Contains EJS templates for rendering pages.
index.ejs: Template for displaying all posts.
form.ejs: Template for creating a new post.
edit.ejs: Template for editing an existing post.
public/: Contains static files such as CSS and JavaScript.

## Dependencies
express: Fast, unopinionated, minimalist web framework for Node.js.
ejs: Embedded JavaScript templates.
uuid: For generating unique IDs.
method-override: Lets you use HTTP verbs such as PUT or DELETE in places where the client doesn't support it.

## Acknowledgements
Special thanks to the open-source community for providing all the tools and libraries used in this project.


