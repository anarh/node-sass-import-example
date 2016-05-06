# node-sass-import-example

## Summary

Example showcasing usage of node-sass-import module

## Install

```sh
$ npm install node-sass-import-example --save-dev
```

## Usage
This package can be imported/required like any npm package so long as the final npm build tool uses [node-sass](https://www.npmjs.com/package/node-sass) and [node-sass-import](https://www.npmjs.com/package/node-sass-import)

The example `.scss` file

```scss
@import 'node-sass-import-example';
```
The example `.html` file

```html
<div class="node-sass-import-example">
  <p>You can now use css rules from the imported scss</p>
</div>
```

## Example

See the `/example` directory for more examples

## Contribution

1. CLONE this repository
2. `npm install`
3. `npm run build`
4. MAKE your changes
5. COMMIT your changes
6. RUN either `npm version patch` or `npm version minor` or `npm version major` depending on the kind of changes you make. 

Running the last command(#6) will **automatically**

 * TAG both the package.json and the stash repo,
 * UPDATE the dependencies in package.json, and
 * PUSH your changes up to the repo.

## License

2016 MIT ©
