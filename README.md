# postcss-test-01

## purpose
- Test CSS building with PostCSS replacing Node-sass.
- Basically stolen from https://github.com/craigbuckler/postcss-demo.git

## Prerequisits / current environment
```zsh
$ node -v
v18.17.0
$ npm -v
9.6.7
```

## Setup

### A) Install with yarn
```zsh
yarn
```

## B) Config browserslist
- defined in .browserslist
- show supported browsers: npx browserslist
```zsh
# old: npx browserslist@latest --update-db
# new:
npx update-browserslist-db@latest
```

## C) Build css
1. production:  ```npx postcss src/scss/main.scss --env production  -o output/main.css```
2. development: ```npx postcss src/scss/main.scss --env development -o output/main-dev.css --verbose```
3. watching:    ```npx postcss src/scss/main.scss --env development -o output/main-watch.css --verbose --watch```


