# A Simple PWA Demo with Next.js

### Steps:

1.) **Initial setup:**

`npx create-next-app my-app`

`cd my-app`

`npm install next-pwa`

`touch next.config.js` and add withPWA configuration


2.) **Create manifest.json file:**

To do so, go [here](https://app-manifest.firebaseapp.com/), download .zip folder and unzip it.

Copy the manifest.json from your download folder to your /public folder inside Next.js PWA project.

Also, copy the contents of /images from the download folder, to the /public folder of your project.


3.) **Create the meta tags:**

You can generate your custom favicon [here](https://www.favicon-generator.org/).

Add the meta tags inside <Head> tag for every page of your app.



4.) **Test your PWA:**

`npm run build`

`npm start`

Go to http://localhost:3000 and run the Lighthouse audit.

Your score should be 95-99 (it will be 100 when you deploy your app with an SSL encryption).

Finally, out of the box, you get caching, offline support and an "Add to Home Screen" prompt will appear on Chrome on mobile devices.
