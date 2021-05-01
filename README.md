# Guide
https://reactjs.org/tutorial/tutorial.html#lifting-state-up

# Deployment
https://chrishart0.github.io/learn-react/

Utilizing yarn `gh-pages` package in order to deploy to gh-pages easily

Added the following to the `scripts` section of package.json in order to get the deploy to work:
```
"predeploy": "npm run build",
"deploy": "gh-pages -d build",
```