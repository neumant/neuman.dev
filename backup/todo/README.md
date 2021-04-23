Markdown Notes
==============

A note taking web app that supports markdown.

**The `/build` folder contains the already built app with an index.html that you can run with an http-server**
You can also see it running live at [markdown-notes](https://dna113p.github.io/markdown-notes)

---

The source code for the app is found in the `/src` folder.

The build system for this is based off of [create-react-app](https://github.com/facebookincubator/create-react-app/issues).
and uses webpack, babel, and autoprefixer to build a ReactJS driven javscript app.

Relevent commands with npm installed:
### `npm install`

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!
