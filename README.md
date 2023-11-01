## Installing and running the project:

```sh
git clone https://github.com/LinemediaDev/FrontendInterview.git
cd FrontendInterview
npm install
npm run dev
```
After running the above commands open project on https://localhost:3000

## Files you need to work with:
1) `app.js` - configured with [express](https://expressjs.com/en/guide/routing.html), renders the `index.html` file
1) `public/index.html` - html file that rendering on https://localhost:3000
1) `public/index.js` - js file that including by the `public/index.html`
1) `db.json` - contains the list of articles

## What to do:
1) In the `app.js` realise the `app.get('/items/'` route that returns the list of articles from the `db.json` file
1) In the `public/index.js` load the data from the `/items/` route and display list of articles in the `.articles` element
1) Configure a pagination for the list of articles (5 articles per page). Use predefined styles from the `public/index.css` file.