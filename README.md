# quick-build

This is a repo uses an existing pre-built container as the base image and nothing else.
This is to test a quick build and deploy where the build should take minimal time and the application is still deploy in an e2e Stone Soup demo. 

```
FROM quay.io/jduimovich0/single-nodejs-app 
CMD [ "node", "app.js" ]
```
