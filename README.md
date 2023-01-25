# quick-build

This is a repo uses an existing pre-built container as the base image and nothing else.
This is to test a quick build and deploy where the build should take minimal time. 

```
FROM quay.io/jduimovich0/single-nodejs-app 
CMD [ "node", "app.js" ]
```
