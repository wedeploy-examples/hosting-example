# WeDeploy Hosting Demo

This template will help you through the process of deploying a WeDeploy Hosting service.

> [Visit the documentation to learn how to start hosting static files.](https://wedeploy.com/docs/deploy/)

## How it works

For hosting static files with our [Hosting Service](https://wedeploy.com/docs/hosting/), any files you deploy within the same folder as your `wedeploy.json` will be served as static files.

Files put into the special directory `/_error` are mapped as the error files to be served in case of an error. They must take the form of `<error code>.html`.


