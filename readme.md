# October CMS Template Theme

## Fontawesome

### Pro
If you have access to the Fontawesome Pro NPM repository, you'll have to use your access token to connect the pro NPM repository before installing the dependencies:

```
npm config set "@fortawesome:registry" https://npm.fontawesome.com/ && \
npm config set "//npm.fontawesome.com/:_authToken" 00000000-0000-0000-0000-000000000000
```

### Free
If you're using the free version of Fontawesome, replace the pro dependency with the free version:
```
yarn remove @fortawesome/fontawesome-pro
yarn add @fortawesome/fontawesome-free
```