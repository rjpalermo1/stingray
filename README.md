# meteor-boilerplate

A starting point for MeteorJS applications. Includes flow-router, Material design Lite, Sass and more.

* [Included Packages](#included-packages)
* [Installation](#installation)
* [Linting](#linting)
* [File Structure](#file-structure)
* [SEO](#seo)
* [Favicons and Touch Icons](#favicons-and-touch-icons)

## <a name="included-packages"></a> Included Packages

* Collections:
  * [aldeed:simple-schema](https://atmospherejs.com/aldeed/simple-schema)
  * [aldeed:collection2](https://atmospherejs.com/aldeed/collection2)
* Router:
  * [kadira:flow-router](https://atmospherejs.com/kadira/flow-router)
  * [kadira:blaze-layout](https://atmospherejs.com/kadira/blaze-layout)
  * [meteorhacks:fast-render](https://atmospherejs.com/meteorhacks/fast-render)
  * [tmeasday:html5-history-api](https://github.com/tmeasday/meteor-HTML5-History-API)
* Authentication
  * [accounts-password](https://atmospherejs.com/meteor/accounts-password)
  * [accounts-ui](https://atmospherejs.com/meteor/accounts-ui)
  * [alanning:roles](https://atmospherejs.com/alanning/roles)
* [Sass](http://sass-lang.com)
  * [fourseven:scss](http://getbootstrap.com)
* PostCSS
  * [juliancwirko:postcss](https://atmospherejs.com/juliancwirko/postcss)
  * [autoprefixer - npm](https://www.npmjs.com/package/autoprefixer)
* Linting
  * [eslint](https://www.npmjs.com/package/eslint)
  * [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb)
  * [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)
  * [eslint-plugin-meteor](https://www.npmjs.com/package/eslint-plugin-meteor)
  * [sass-lint](https://www.npmjs.com/package/sass-lint)
    * [airbnb - css](https://github.com/airbnb/css)
* Misc:
  * Touch Support:
    * [hammerjs - npm](https://www.npmjs.com/package/hammerjs)
  * [Material Design Lite - NPM](https://getmdl.io/)

## <a name="installation"></a> Installation

1. Clone this repo to `<yourapp>`

  `https://github.com/MichaelJosephMiller/meteor-boilerplate.git <yourapp>`

2. Install NPM packages

  `npm install`

3. Set new remote url

  `git remote set-url <name> <newurl>`

4. Start coding!

## <a name="linting"></a> Linting

Javascript: `npm run js-lint`

CSS & Sass: `npm run sscss-lint`

## <a name="file-structure"></a> File Structure

We have a common file structure we use across all of our Meteor apps. Client-only files are stored in the `client` directory, server-only files are stored in the `server` directory, and shared files are stored in the `common` directory. The `private` and `public` directories are for either private or public assets. 

## <a name="seo"></a> SEO

SEO is handled by [dfischer:prerenderio](https://atmospherejs.com/dfischer/prerenderio) and [kadira:dochead](https://atmospherejs.com/kadira/dochead) packages. Follow instructions on the respective sites for settup.

## <a name="favicons-and-touch-icons"></a> Favicons and Touch Icons

Upload your image to http://realfavicongenerator.net/ and place the resulting images in `public/images/favicons`
Copy and paste the HTML5 code to /client/head.html
