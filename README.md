# React App on GitHub Pages

Maybe this could work as a boilerplate for your project. The trick is the following `build` command.

```json
"scripts": {
  "start": "react-scripts start",
  "build": "react-scripts build && rm -rf docs && mv build docs",
  "test": "react-scripts test --verbose",
  "eject": "react-scripts eject"
  },
```

## Getting started
1. Clone this repository.
1. Type `yarn` to your terminal. This will install the dependencies.
1. Type `yarn start` to test this website. It will open the website on your default browser.
1. Type `yarn build` to build this website. It will create an optimized version for production in the `docs` folder.
1. Commit and push to GitHub.
1. Go to Repository Settings, General, GitHub Pages. Select Branch `master` or `main`, and select `docs`.
1. Whenever you build and push, the React App will automatically be distributed to your domain.