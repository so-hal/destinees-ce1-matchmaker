# MatchMaker

This repository includes the new MatchMaker feature Acme has developped to help users find the right training from their criteria.

## Requirements

- Node.js version >= 20
- VSCode: this is the IDE we use at Acme for coding. The project contains VSCode-specific configuration.
- yarn - from a terminal: `npm install -g yarn`
- git

## Admin

This repository includes the MatchMaker admin app to manage users and partners from the MatchMaker front app.

To access the production admin:

URL: https://acme.com/admin
Credentials have been moved to LastPass. Please request access from your manager.

### To run from your computer

Install the dependencies:

```bash
yarn install
```

Run the app:

```bash
yarn dev:admin
```

## Front app

Install the dependencies:

```bash
yarn install
```

Run the app:

```bash
yarn dev
```

Run tests:

```bash
yarn test
```

Optionally, you can use a VSCode plugin like Jest Runner to make running tests easier, especially if you want to run only some specific tests, instead of all tests.

Note: we could also add a watch command to let the tests run in background while we develop. Feel free to add the script or ask your tech lead to get help on that.

## Deployment

### Test server

The admin app is automatically deployed on our test server once your contribution is pushed to the main branch.

### Production server

Production deployments happen when merged to the `production` branch. This branch is protected, thus merging requires approval from a tech lead or above on your Pull Request.
