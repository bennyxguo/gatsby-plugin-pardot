# gatsby-plugin-pardot

Easily add the [Pardot](https://www.salesforce.com/) analytics to your Gatsby site.

> Updated version of [original gatsby-plugin-pardot](https://github.com/Energizz/gatsby-plugin-pardot) from 2 years ago.

## Install

`npm install --save gatsby-plugin-pardot`

## How to use

```javascript
// In your gatsby-config.js
plugins: [
  {
    resolve: `gatsby-plugin-pardot`,
    options: {
      piAId: 'YOUR_PIAID',
      piCId: 'YOUR_PICID',
      includeInDevelopment: false
    }
  }
];
```
