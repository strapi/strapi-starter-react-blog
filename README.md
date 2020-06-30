# Strapi Starter React Blog

React starter for creating a blog with Strapi.

This starter allows you to try Strapi with React with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. Do not hesitate to add new features etc ...

You may want to know how to develop such a starter by your own! This starter is actually the result of this [tutorial](https://strapi.io/blog/build-a-blog-with-react-strapi-and-apollo)

![screenshot image](/screenshot.png)

### Deploy the backend

To deploy the Strapi instance you'll need:

- [An Heroku account](https://signup.heroku.com/) for free
- [A Cloudinary account for saving images](https://cloudinary.com/users/register/free) for free

Once you have created these accounts you can deploy your instance by clicking on this button

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/strapi/strapi-starter-blog)

[Here](https://github.com/strapi/strapi-starter-blog) is the repository of the backend of this starter

### Deploy the frontend

**On Netflify**

To deploy this frontend you'll need:

- [A Netilfy account](https://app.netlify.com/signup) for free

Once you have created your account, add the url of your Heroku instance  (without the trailing slash) as a parameter to the following url.

https://app.netlify.com/start/deploy?repository=https://github.com/strapi/strapi-starter-react-blog#REACT_APP_BACKEND_URL=<your-strapi-app.herokuapp.com>

- Visit this url to deploy your application

**On Vercel**

Coming soon...

### Features

- 2 Content types: Article, Category
- 2 Created articles
- 3 Created categories
- Permissions set to `true` for article and category
- Responsive design using UIkit

### Pages

- "/" display every articles
- "/article/:id" display one article
- "/category/:id" display articles depending on the category

### Getting started

**Backend**

See full instructions [here](https://github.com/strapi/strapi-starter-blog)

**Frontend**

```bash
git clone https://github.com/strapi/strapi-starter-react-blog.git
cd strapi-starter-react-blog
```

#### Start the frontend server

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

Enjoy this starter
