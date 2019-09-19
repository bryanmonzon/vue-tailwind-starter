# vue-tailwind-starter

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


### Tailwind Stuff
- Added `postcss.config.js`
- Removed the postcss section from `package.json`
```
  "postcss": {
    "plugins": {
      "autoprefixer": {}
    }
  },
```
- Added `import './main.css'` in `App.vue`
