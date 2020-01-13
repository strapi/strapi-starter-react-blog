# React Strapi Blog Starter

Strapi starter for creating a blog with React.

This starter allows you to try Strapi with React with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. Do not hesitate to add new features etc ...

You may want to know how to develop such a starter by your own! This starter is actually the result of this [tutorial](https://strapi.io/blog/build-a-blog-with-react-strapi-and-apollo)

![screenshot image](/screenshot.png)

### Features

- 2 Content types: Article, Category
- 2 Created articles
- Apollo integration (GraphQL) for fetching data from strapi
- Responsive design using UIkit

### Pages

- "/" display every articles
- "/articles/:id" display one article
- "/category/:id" display articles depending on the category

### Getting started

*Clone the repository and install dependencies*

```
git clone https://github.com/strapi/react-strapi-blog-starter.git
cd react-strapi-blog-starter
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

### Other blog starters

  - Vuejs Strapi Blog Starter, work in progress...
  - Gatsby Strapi Blog Starter, 6 february
  - Next.js Strapi Blog Starter, 20 february
  - Nuxt.js Strapi Blog Starter, 6 March
