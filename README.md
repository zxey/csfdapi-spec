# Csfd OpenAPI Specification

Work In Proggress implementation of this api in Rust: [here](https://github.com/zxey/csfdapi)

[![Build Status](https://travis-ci.com/zxey/csfdapi-spec.svg?branch=master)](https://travis-ci.com/zxey/csfdapi-spec)

## Links

- Documentation(ReDoc): https://zxey.github.io/csfdapi-spec/
- SwaggerUI: https://zxey.github.io/csfdapi-spec/swagger-ui/
- Look full spec:
    + JSON https://zxey.github.io/csfdapi-spec/swagger.json
    + YAML https://zxey.github.io/csfdapi-spec/swagger.yaml
- Preview spec version for branch `[branch]`: https://zxey.github.io/csfdapi-spec/preview/[branch]

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

### Usage

1. Run `npm start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing https://zxey.github.io/csfdapi-spec/ with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
6. Share you changes with the rest of the world by pushing to GitHub :smile:
