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
- navbar
  - title
  - logo
  - items
- footer
```js
      footer: {
        style: 'dark',
        links: [
          {
            title: 'Docs',
            items: [
              {
                label: 'Tutorial',
                to: '/docs/intro',
              },
            ],
          },
          {
            title: 'Community',
            items: [
              {
                label: 'Contribution',
                href: '#',
              },
              {
                label: 'Discord',
                href: '#',
              },
              {
                label: 'The Bored Company',
                href: '#',
              },
            ],
          },
          {
            title: 'More',
            items: [
              {
                label: 'About the author',
                to: '#',
              },
              {
                label: 'GitHub',
                href: '#',
              },
            ],
          },
        ],
        copyright: `Copyright © ${new Date().getFullYear()} The Bored Company, Built with Docusaurus.`,
      },
```
