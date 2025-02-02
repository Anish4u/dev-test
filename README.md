# Labzone - FE Developer Skill Test

A simple test app to ascertain developer skill-level.

The challenge is to create a basic app using HTML, CSS, JavasScript - React.js and the Flickr API.

The app should demonstate your ability to set up a React App, load in some photos from Flickr (JSON format) [public API](https://api.flickr.com/services/feeds/photos_public.gne?format=json) and display the photo, name and description in a card layout. The images should be clickable and link to the content. The app should have a header and a footer and ideally be responsive.

Bonus points will be awarded for a working search box, loading more photos on scroll and any other visual improvements or animations that you would like to add.

Please fork this repository and create pull request when you are done.

If you do wish to use other Flickr API feeds, be aware that some endpoints do require an API key. You can register for an API key [here](https://www.flickr.com/services/apps/create/).

More documentation on the API can be found on [this link](https://www.flickr.com/services/api/).

Pixel perfect mockup to design is a real focus for us at Labzone, the mockup for the test can be found @ https://www.figma.com/file/WnxpAKMFJkzvcrzf4h8vok/Flickr-App (you will need to login to see design details / sidebar)



### Good luck !

## Flicker App
This project is a Frontend system implemented in React with  TypeScript to handle to  demonstate  to set up a React App, load in some photos from Flickr (JSON format) [public API](https://api.flickr.com/services/feeds/photos_public.gne?format=json) and display the photo, name and description in a card layout. The images should be clickable and link to the content. The app should have a header and a footer and ideally be responsive.

## Prerequisites

Make sure you have latest version of Node.js and npm installed on your machine.

- Node.js: [https://nodejs.org/]
- npm: [https://www.npmjs.com/]

## File Structure For Frontend
```
frontend
src/
|-- components/
|   |-- hooks/
|       |-- useFetch.tsx
|       |-- useLoader.tsx
|       |-- useObserver.tsx
|
|   |-- cardGallery.tsx
|   |-- cards.tsx
|   |-- footer.tsx
|   |-- header.tsx
|   |-- search.tsx
|
|-- constants.ts
|-- App.tsx
|-- css/
|   |--main.css
```

## Installation for frontend

```bash
$ cd saidot-flickr-app
$ npm install 
```
##  How to start frontend

```bash
# development
$ npm start 
```

To verify that the application started sucecssfully in local navigate to http://localhost:3000 in your web browser.
