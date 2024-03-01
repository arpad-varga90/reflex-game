# hit-me-baby

## Tutorial

0. clone
1. npm init -y
3. delete the main:... line from package.json
4. npm i parcel
5. npm i gh-pages
6. npm i rimraf
7. add .gitginore with node_modules and dist folder as a content
```
node_modules
dist
```
8. Write your app

```
"build": "rimraf dist && parcel build './src/**/*.html' --no-cache"
```

```
"start": "rimraf dist && parcel serve './src/**/*.html' --no-cache --open",
```

```
"deploy": "gh-pages -d dist"
```
