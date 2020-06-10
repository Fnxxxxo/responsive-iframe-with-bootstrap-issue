# responsive-iframe-with-bootstrap-issue

> Issue: bootstrap.css break the responsive iframe.

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev
```

## Reproduce
```
// Close all bootstrap.css in /nuxt.config.js

bootstrapVue: {
  bootstrapCSS: false
},

// Run with dev and check http://localhost:3000/frame.html. A embeded panel within dark background shows.

// Open all bootstrap.css
bootstrapVue: {
  bootstrapCSS: true
},

// After hot-reload, refresh the page. The whole embeded page shows. The fixed size of html not work.

```
