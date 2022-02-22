# @qest/tsconfig-react

This aims to provide easy and consistent typescript settings for all our react projects.

## instalation

``` bash
yarn add -D typescript @qest/tsconfig-react
```

``` js
// tsconfig.json
module.exports = {
  "extends": "@qest/tsconfig-react",
  // "compilerOptions": {
  //   "baseUrl": "src",
  //   "paths": {
  //     "assets/*": [
  //       "assets/*"
  //     ],
  //     "components/*": [
  //       "components/*"
  //     ],
  //     "layouts/*": [
  //       "layouts/*"
  //     ],
  //     "styles/*": [
  //       "styles/*"
  //     ],
  //     "utils/*": [
  //       "utils/*"
  //     ],
  //     "hooks/*": [
  //       "hooks/*"
  //     ]
  //   }
  // }
};
```
