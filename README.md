# fast-build

This is a repo that has a Dockerfile and a random devfile copied from samples which uses that Dockerfile to build.

The Dockerfile is a stripped down file which basically packages up and existing image and no additiona work performed

```
FROM quay.io/jduimovich0/single-nodejs-app 
CMD [ "node", "app.js" ]
```