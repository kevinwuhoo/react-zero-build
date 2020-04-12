# Zero build and config React boilerplate

## Rationale

Have you ever wanted to get a quick idea onto the internet?
[create-react-app](https://github.com/facebook/create-react-app) is pretty good,
but is still relatively complex and requires a build to deploy.

The idea behind a boilerplate like this is to eliminate the need to build and to
simplify deployment on simple projects. A site built using this boilerplate can
be served using only a static file server.

Obviously, the trade off is that there is no equivalent to create-react-app's
`eject` functionality. However, once it reaches that level of complexity, it
should be easy to copy paste any existing code into another boilerplate.

## Usage

To use this for devlopment, first do a `npm install` which installs a few
development dependencies. Afterward, run `npm run dev` to start a dev server
which auto-restarts on any file change.
