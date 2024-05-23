# Node-Express-TypeScript template

This project is created as a template to start any Node-Express project using typescript
## Scripts

### `npm start`
Application starts with watch mode on.

### `npm build`
Application build package is created in `./dist` folder.

### `postbuild`
The current script depends on linux's `cp` (copy) command.
The user has to change it according to their operating system.
> The developer does not have to run this as
> it will automatically run after `npm build`

### `npm run test`

Run all existing test cases

## Features

1. TypeScript execution engine : [`tsx`](https://www.npmjs.com/package/tsx)
2. Live reload : [`livereload`](https://www.npmjs.com/package/livereload), [`connect-livereload`](https://www.npmjs.com/package/connect-livereload)
3. dotenv configuration : [`dotenv`](https://www.npmjs.com/package/dotenv)

## Testing

Tests can be run without building the code with the help
of [`ts-jest`](https://www.npmjs.com/package/ts-jest)

1. Utility Unit testing : [`Jest`](https://jestjs.io)
2. Request Unit testing : [`SuperTest`](https://www.npmjs.com/package/supertest)

## Other information

1. Template engine : [`pug`](https://www.npmjs.com/package/pug)
2. HTTP request logger middleware : [`morgan`](https://www.npmjs.com/package/morgan)
