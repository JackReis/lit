# lit 🔥
<a href="https://twitter.com/intent/tweet?text=World's+smallest+responsive+CSS+framework:&url=https%3A%2F%2Fgithub.com%2Fajusa%2Flit&hashtags=github&original_referer=http%3A%2F%2Fgithub.com%2F&tw_p=tweetbutton" target="_blank">
  <img src="http://jpillora.com/github-twitter-button/img/tweet.png"
       alt="tweet button" title="lit"></img>
</a>

a ridiculously small responsive css framework.

I challenged myself to see how small I could go, but preserve everything Skeleton, Milligram, and other micro frameworks have to offer.
## Features
* 12 Column Responsive Grid
* Typography for h1-h6, and body text
* Three types of buttons
* Cards
* Inputs
* Table Styles

and a little bit more...

## Getting Started
1. Install lit.css with one of the following:
  - NPM: `npm install --save @ajusa/lit`
  - CSS3: `<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@ajusa/lit@1.0.0/dist/lit.css)" />`
  - CSSNext: `<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@ajusa/lit@1.0.0/src/lit.css)" />`
2. [Read the Docs](https://ajusa.github.io/lit/) to see usage

Note: lit uses PostCSS to transform from CSSNext to CSS3. If you are comfortable outright using CSSNext, you can directly
include the `lit.css` file in the src directory. Otherwise, use the `dist/lit.css` file.

## Supported Browsers
lit supports most modern browsers (Chrome, Firefox, Edge, Opera) but it also has impressive support for older browsers.
lit has been tested on Internet Explorer 11 with no issues.

## Development Setup
1. Clone this repository (https://www.github.com/ajusa/lit)
2. Make sure you have [npm](https://www.npmjs.com/get-npm) installed
3. Run `npm install` in the root directory of `lit`
4. Once that is completed, run `npm run build` to build the minified version and the gzipped file.
5. If you are making changes live, use `npm run watch`. `watch` will build the minified css file in `./dist` whenever there is a change in `./src/lit.css`.
