# Strapi Starter React Blog

React starter for creating a blog with Strapi.

This starter allows you to try Strapi with React with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. Do not hesitate to add new features etc ...

You may want to know how to develop such a starter by your own! This starter is actually the result of this [tutorial](https://strapi.io/blog/build-a-blog-with-react-strapi-and-apollo)

![screenshot image](/screenshot.png)

### Backend and Frontend deployment

Tested on FreeBSD 12.1 with Nginx as reverse proxy enabled.
[![asciicast](https://asciinema.org/a/OJcl9TYA8eWuzsLlh3hFHcf0Y.svg)](https://asciinema.org/a/OJcl9TYA8eWuzsLlh3hFHcf0Y)

### Features

- 2 Content types: Article, Category
- Permissions set to `true` for article and category
- 2 Created articles
- 3 Created categories
- Apollo integration (GraphQL) for fetching data from strapi
- Responsive design using UIkit

### Pages

- "/" display every articles
- "/article/:id" display one article
- "/category/:id" display articles depending on the category

### Getting started

**Clone the repository**

```bash
git clone https://github.com/strapi/strapi-starter-react-blog.git
cd strapi-starter-react-blog
```

### Start the backend server

```bash
cd backend

# Using yarn
yarn
yarn develop

# Using npm
npm install
npm run develop
```

### Start the frontend server

```bash
cd frontend

# Using yarn
yarn
yarn develop

# Using npm
npm install
npm run develop
```

React server is running here => [http://localhost:3000](http://localhost:3000)
Strapi server is running here => [http://localhost:1337](http://localhost:1337)

Enjoy this starter
