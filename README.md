# Influmedia PWA

Influmedia  in progressive web application version utilizing a modern web application architecture leveraging [Service Worker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/) to enable offline application 'shell' and populate the content using JS. 

## Installation

Install dependencies using npm:

```sh
$ npm install -g gulp nodemon && npm install
```

## Usage

### Production Build

```sh
$ gulp
```

### Development Build with Watch

```sh
$ gulp dev
```

### Serve/watch

Once you've got a production build or development build of gulp done, start the
server with:

```sh
$ nodemon server/app.js
```

Alternatively, you can just run `npm run monitor`. The application shell should now be available on port `8080`.

## License

Copyright 2016 MDev Co., Ltd.
