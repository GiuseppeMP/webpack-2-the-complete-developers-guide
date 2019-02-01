# Webpack-2-the-complete-developers-guide

## Section 01 - How to use this Course'.'

## Section 02 - What Does Webpack Do'?'

### lecture 03 - Why Do We Use Build Tools'?'

> Server Side Templating

Backend server creates an HTML document and sends it to the user.

1. User visits page.
2. HTTP Request to server.
3. New HTML Document.
4. User clicks a link.
5. HTTP request to server.
6. new HTML Document.

> Single Page Application

Server sends a bare-bones HTML doc to the user. Javascript runs on the user machine to assemble a full webpage.

1. User visits page.
2. HTTP Request to server.
3. new HTML Document.
4. React/Angular/Vue/Backbone boots up, shows page.
5. User clicks link.
6. React/Angular/Vue/Backbone shows new content.

### lecture 04 - Javascript Modules

SPA -> A lot of js code.

How to organize this gigant javascript applications, so, javascript modules rise.

Javascript module is a file with few js lines.

.
+-- Components Folder
| +-- header.js
| +-- tooltip.js
| +-- dashboard.js
| +-- button.js
| +-- footer.js
| +-- range.js
+-- Components Folder
| +-- fetch.js
| +-- keys.js
| +-- collection.js
| +-- formatter.js
