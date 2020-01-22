# Strapi Starter React Blog

React starter for creating a blog with Strapi.

This starter allows you to try Strapi with React with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. Do not hesitate to add new features etc ...

You may want to know how to develop such a starter by your own! This starter is actually the result of this [tutorial](https://strapi.io/blog/build-a-blog-with-react-strapi-and-apollo)

![screenshot image](/screenshot.png)

### Features

- 2 Content types: Article, Category
- Permissions set to `true` for article and category
- Apollo integration (GraphQL) for fetching data from strapi
- Responsive design using UIkit

### Pages

- "/" display every articles
- "/articles/:id" display one article
- "/category/:id" display articles depending on the category

### Getting started

**Clone the repository and install dependencies**

```
git clone https://github.com/strapi/strapi-starter-react-blog.git
cd strapi-starter-react-blog
yarn setup
```

### Run your React frontend

```
cd frontend
yarn start
```

Server is running here => [http://localhost:3000](http://localhost:3000)

### Run your Strapi backend

```
cd backend
strapi dev
```

Server is running here => [http://localhost:1337](http://localhost:1337)

### What you need to do

Create your admin user and after that you'll only need to create your articles and your categories
To do this, head to your strapi admin panel just right here => [http://localhost:1337/admin](http://localhost:1337/admin)

Enjoy this starter
