# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

### Installation

```
npm i
```

### Local Development

```
$ npm run start
```

start RU locale 

```
$ npm run start -- --locale ru
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Support
```
my-website
├── docs
│   ├── doc1.md
│   ├── doc2.md
│   ├── doc3.md
│   └── imgs
├── i18n
│   └── ru
│       └── docusaurus-plugin-content-docs
│           └── current
│           └── current.json
├── src
│   ├── css
│   │   └── custom.css
│   └── pages
│       ├── styles.module.css
│       └── index.js
├── static
│   └── img
├── docusaurus.config.js
├── package.json
├── README.md
├── sidebars.js
```
Documentation in English is located at /docs. Images in English located in /imgs folder.
Documentation in Russian is located at /i18n/ru/docusaurus-plugin-content-docs/current. Images in Russian located in /imgs folder.
current.json contain translations to Russian common elements.


