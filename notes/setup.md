
```
"predeploy": "npm run build",
"deploy": "gh-pages -d dist",
```

gh-pages automates the Git commit and push process for the dist folder to the gh-pages branch

```
npm install gh-pages --save-dev
npm run deploy
```

