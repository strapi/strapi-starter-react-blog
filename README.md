# Strapi Starter React Blog

> **Warning :warning:**
>
> This starter is deprecated and relies on the deprecated **[strapi/strapi-legacy-blog](https://github.com/strapi/strapi-legacy-blog)** repository.
>
> Instead, we recommend that you use our other React blog starters with better SEO support:
>
> * [**strapi-starter-gatsby-blog**](https://github.com/strapi/strapi-starter-gatsby-blog)
> * [**strapi-starter-next-blog**](https://github.com/strapi/strapi-starter-next-blog)

React starter for creating a blog with Strapi.

This starter allows you to try Strapi with React with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. Do not hesitate to add new features etc ...

You may want to know how to develop such a starter by your own! This starter is actually the result of this [tutorial](https://strapi.io/blog/build-a-blog-with-react-strapi-and-apollo)

![screenshot image](/screenshot.png)

## Features

- 2 Content types: Article, Category
- 2 Created articles
- 3 Created categories
- Permissions set to `true` for article and category
- Responsive design using UIkit

Pages:

- "/" display every articles
- "/article/:id" display one article
- "/category/:id" display articles depending on the category

## Getting started

### Backend

See full instructions [here](https://github.com/strapi/strapi-legacy-blog)

### Frontend

```bash
git clone https://github.com/strapi/strapi-starter-react-blog.git
cd strapi-starter-react-blog
```

Then start the frontend server:

```bash
# Using yarn
yarn install
yarn develop

# Using npm
npm install
npm run develop

# Create a .env file containing the API_URL variable
echo 'SKIP_PREFLIGHT_CHECK=true\nREACT_APP_BACKEND_URL="http://localhost:1337' >> .env
```

React server is running here => [http://localhost:3000](http://localhost:3000)

Enjoy this starter!
