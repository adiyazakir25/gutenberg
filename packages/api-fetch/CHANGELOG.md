# 2.2.0 (Unreleased)

### New Feature

- Always request data in the user's locale ([#10862](https://github.com/WordPress/gutenberg/pull/10862)).

## 2.1.0 (2018-10-22)

### New Feature

- Support `per_page=-1` paginated requests.

## 2.0.0 (2018-09-05)

### Breaking Change

- Change how required built-ins are polyfilled with Babel 7 ([#9171](https://github.com/WordPress/gutenberg/pull/9171)).  If you're using an environment that has limited or no support for ES2015+ such as lower versions of IE then using [core-js](https://github.com/zloirock/core-js) or [@babel/polyfill](https://babeljs.io/docs/en/next/babel-polyfill) will add support for these methods.
