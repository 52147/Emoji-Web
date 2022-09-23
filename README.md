# Emoji-Web

## Deploy react App to github page
- Intstall Node and npm
- Install yarn package

```
npm install -g yarn
```
- Install github page packages in your devDependencies
```
yarn add -D gh-pages
```
or 
```
npm install gh-pages --save--dev
```

## Modify package.json

- Add web url
```
"homepage":"https://52147.github.io/Emoji-Web/"
```
- Add 2 scripts in scripts doc

```
"predeploy": "npm run build",
"deploy": "gh-pages -d build",
```
## Push the changes to Github
```
git add *
git commit -m "update"
git push
```

## Deploy the site to the Github page branch
```
npm run deploy
```
## Go to Settings Pages to change the branch
Change branch to Github page to build the site

