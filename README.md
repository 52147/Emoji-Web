# Emoji-Web

## Deploy react App to github page
- intstall Node and npm
- install yarn package

```
npm install -g yarn
```
- install github page packages in your devDependencies.
```
yarn add -D gh-pages
```
or 
```
npm install gh-pages --save--dev
```

## modify package.json

- Add web url
```
"homepage":"https://52147.github.io/Emoji-Web/"
```
- add 2 scripts in scripts doc

```
"predeploy": "npm run build",
"deploy": "gh-pages -d build",
```
push the changes to Github
```
git add *
git commit -m "update"
git push
```
