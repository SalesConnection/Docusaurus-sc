# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ npx create-docusaurus@latest <my-website> classic
```

### Local Development

```
npm install
$ cd <my-website>
npm run start

port 3000
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
Docusaurus is a modern static website generator so we need to build the website into a directory of static contents and put it on a web server so that it can be viewed. To build the website:

$ npm run build
- Build already configured
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
