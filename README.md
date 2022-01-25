# Botify Test Skeleton

Based on [Create React App](https://github.com/facebook/create-react-app), but stripped of all the code irrelevant to the test.

## Installation

```sh
# Clone the repository
git clone git@github.com:botify-labs/botify-js-test-skeleton.git botify-test

# Install the dependencies
cd botify-test/
npm install
```

## Development

Launch the development server on http://localhost:3000/ using: `npm start`.

Your starting point should probably be `src/App.js`.

## How tests are evaluated?

Here are a few tips regarding how we evaluate tests:
- Code should work
- Code should be clean (easy to read, comments where relevant, follow good practices, etc)
- Code should be a simple as possible (avoid language tricks, one-liners, and generally everything that impedes code-review)
- Git history should be as clean as possible (good commit names, commits are not too small or too big, branches are used when asked, etc)
- We don't really look at the styling, so don't spend too much time making everything pixel perfect
- Only spend as much time as you can afford: we'd rather review half of the features, than nothing at all
- If you're having issues with the test, feel free to message us!