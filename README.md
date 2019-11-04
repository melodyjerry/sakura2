Sakura v2
====

[![Build Status](https://dev.azure.com/moezhx/sakura2/_apis/build/status/mashirozx.sakura2?branchName=master)](https://dev.azure.com/moezhx/sakura2/_build/latest?definitionId=1&branchName=master)

[Demo](https://mashirozx.github.io/sakura2/dist/)

I'll build the basical templates here, the stylesheets and scripts in `dist` folder should work on WordPress front end as well. 

```bash
npm i -g webpack-cli
npm install
# Run dev server
cp -r ./src/img ./dist
npm start
# Build
npm run build
# If need a release
```

Dev server on <http://localhost:8080/>

[Notes](./NOTES.md)