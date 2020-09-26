# webfactory Browserslist Shared Config

This configuration reflects webfactory's default supported browser policy for their client projects.

## What is Browserslist?

Share browsers list between different front-end tools, like Autoprefixer, Stylelint and babel-preset-env.

- [Browserslist](https://github.com/ai/browserslist) (Github repo)
- [browserl.ist](http://browserl.ist) (Browserslist query syntax validation)
- ["Browserslist is a Good Idea"](https://css-tricks.com/browserlist-good-idea/) (blog post by [@chriscoyier](https://github.com/chriscoyier))

## Default browser support

- last 2 versions of major browsers
- IE11
- 99.5% coverage in DE

## Install

```js
yarn add --dev browserslist-config-webfactory
```

## Usage

### package.json

```json
{
  "browserslist": ["extends browserslist-config-webfactory/default"]
}
```

## Alternative configuration

_Alternative configurations will be added on demand._
