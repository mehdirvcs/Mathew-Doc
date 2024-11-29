# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Clone

```
$ git clone https://gitlab.com/solace-studios/Matthew
```

### Installation

```
$ npm init docusaurus
$ npm install
```

### Local Development

```
$ npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.


### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true npm run serve
```

Not using SSH:

```
$ GIT_USER=<Your Gitlab username> npm run serve
```

Using Netlify:

Follow prompts
```
https://app.netlify.com/start
```
