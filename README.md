# API Docs Demo OpenAPI Specification
[![Build Status](https://travis-ci.com/michaelfahmy/api-docs-demo.svg?branch=master)](https://travis-ci.com/michaelfahmy/api-docs-demo)

## Links

- [Reference Documentation (ReDoc)](https://michaelfahmy.github.io/api-docs-demo/)
- OpenAPI Raw Files: [JSON](https://michaelfahmy.github.io/api-docs-demo/openapi.json) [YAML](https://michaelfahmy.github.io/api-docs-demo/openapi.yaml)

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `yarn install` in the repo root

### Usage

#### `yarn start`
Starts the development server.

#### `yarn run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `yarn test`
Validates the spec.

#### `yarn run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
