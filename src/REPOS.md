# Repositories

## kabocha/Substrate Apps

The [apps](https://github.com/kabocha-js/apps) repo hosts the kabocha-JS interface. This is a general React UI that can be used to interact with your kabocha/Substrate node. There are a number of hosted versions of the code available for your use, these include -

- [kabocha/Substrate](https://kabocha.js.org/apps/) - this is updated as code is merged to the `master` branch and always has the latest available features;

## API

The [api](https://github.com/kabocha-js/api) repo hosts the `@kabocha/api` package, a fully-featured API library to interact with kabocha and Substrate nodes. It is fully [documented](https://kabocha.js.org/api/) and comes with [examples](https://kabocha.js.org/api/examples/promise/) to quickly get you started in developing applications.

It is provided in 2 flavours, a Promise-based version (using callbacks for subscription interfaces) and an RxJs-based version, using Obervables all the way through.

## Extension

The [extension](https://github.com/kabocha-js/extension) repo is an account management extension, allowing you to store your accounts securely locally to your browser and inject these into any compatible dapps. It does not provide any transactional funcionality, but rather llows you to sign any transactions and messages.

## Common utilities

The [common](https://github.com/kabocha-js/common) repo hosts a collection of utilities that are useful to application developers using the APIs. As with the API, it is fully [documented](https://kabocha.js.org/common/) allowing for real-world use of the `@kabocha/util`, `@kabocha/util-crypto` and `@kabocha/keyring` libraries.

## UI Libraries

The [ui](https://github.com/kabocha-js/ui) repo hosts a set of browser based utilities in addition to React components that we have developed. It does not try to force our way of thinking on the user, rather focusses on the base components, such as managing chain settings (`@kabocha/ui-settings`), balance formatting (`@kabocha/ui-util`) and displaying identity icons (`@kabocha/ui-identicon`, in a variety of flavours). [Documentation](https://kabocha.js.org/ui/) is available for the exposed packages.

## Client

The [client](https://github.com/kabocha-js/client) repo is an alternative implementation of a kabocha Runtime Environment (PRE), written from the ground up to perform the function of a full node in the network. (Full block validation, no block authoring). Currently it is still in heavy development, not quite ready for alpha.

## Tools

The [tools](https://github.com/kabocha-js/tools) repo hosts a growing collection of commandline tools that can be used to manage and monitor nodes.
