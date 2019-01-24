# Shop with Blog Example with css, scss and css module files (based on Deity Falcon v0.3)

Take a look at [this commit](https://github.com/mateuszwozniak/falcon-with-scss/commit/6dbcfc8400161b92f5935fd38528cb6fb0dfd745) to see how you can add your own css, scss and css/scss modules to Falcon app.

---

This is a template which is used by [`create-falcon-app`](https://github.com/deity-io/falcon/tree/master/packages/create-falcon-app) to create a shop with blog app.

## Quick Start

The best place to start is to use [`create-falcon-app`](https://github.com/deity-io/falcon/tree/master/packages/create-falcon-app#create-falcon-app). 

Or download the example [or clone the whole project](https://github.com/deity-io/falcon.git):

Install it and run:

```bash
yarn install
yarn start
```

Then open http://localhost:3000/ to see your app.

**That's it**. Just start editing `./src/App.js` and go!

## Testing

To run tests:

```bash
yarn test
```

This will run the test watcher (Jest) in an interactive mode. By default, runs tests related to files changed since the last commit.


## Debugging

To run with debugger:

```bash
yarn start:dbg
```

This will start application with enabled inspector agent.

If the server should wait till debugger will attache then run:

```bash
yarn start:dbg-brk
```

For more information, see [`falcon-client start`](https://github.com/deity-io/falcon/tree/locales/packages/falcon-client#falcon-client-start------inspecthostport) command.

## Production package

To build and run production package:

```bash
yarn build
yarn start:prod
```

You could view your application at http://localhost:3000

## More information

If you would like to find more information please check out the official documentation website [https://falcon.deity.io/](https://falcon.deity.io/)
