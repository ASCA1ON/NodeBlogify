# Blog App

A simple blogging application built with Node.js, Express, MongoDB, and EJS. 

## Features

- Create, edit, and delete blog articles
- Use Markdown for article content
- Clean design

## Usage

### Install Dependencies

```
npm install
```

### Configure Environment Variables

Create a `.env` file and add the following:

```
DATABASE_URL=<your mongodb database url> 
```

### Run the App

```
npm run dev
```

The app will run on http://localhost:5000

### Create an Article 

- Go to the *New Article* page
- Add a title, description, and content in Markdown
- Click *Save* 

You will be taken to newly created articles page
The article will now show up on the home page.

### Edit an Article

- Click the *Edit* button on any article
- Modify the title, description, or content 
- Click *Save*

### Delete an Article

- Click the *Delete* button on any article

The article will be removed from the blog.

## Built With

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/) 
- [EJS](https://ejs.co/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [Marked](https://github.com/markedjs/marked)
- [dompurify](https://github.com/cure53/DOMPurify)
- [JSDOM](https://github.com/jsdom/jsdom)
- [slugify](https://github.com/sindresorhus/slugify)
