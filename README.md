# docusaurus-automation

Well, even though this reporitory is called automation, actually, it's not.

## STEP1: JSON file settings
- title
- tagline
- url
- baseurl
- favicon
- organizationName
- projectName
- prism(for additional languages highlighting)
```js
module.exports = {
  // ...
  themeConfig: {
    prism: {
      additionalLanguages: ['powershell'],
    },
    // ...
  },
};
```
