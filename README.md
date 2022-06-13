# ship-it-out-client v3

shipItOut-client practice with yarn, TypeScript, Cypress, react-router-dom v6, MUI v5, Formik, Yup, ESLint, Prettier, or at least that's the plan.

Maybe i'll add atom, graphql, ect as well.

TODO:

Run

```
pnpm install --save @babel/plugin-syntax-flow @babel/plugin-transform-react-jsx @babel/core @testing-library/dom @types/testing-library__jest-dom

```

to deal with yarn 3.2.0 startup issues

```
Compiled successfully!

You can now view ship-it-out-client in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://192.168.1.65:3000

Note that the development build is not optimized.
To create a production build, use yarn build.

webpack compiled successfully
ERROR in src/App.test.tsx:1:19
TS2307: Cannot find module 'react' or its corresponding type declarations.
  > 1 | import React from 'react';
      |                   ^^^^^^^
    2 | import { render, screen } from '@testing-library/react';
    3 | import App from './App';
```

![image](https://user-images.githubusercontent.com/5026476/173350361-b1af513e-5081-4269-ad03-9179985adff5.png)

For making it work with vscode

```
yarn dlx @yarnpkg/sdks vscode
```

so vscode can resolve any yarn 3 dependencies.
