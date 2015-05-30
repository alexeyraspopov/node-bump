# version-bump

Update project version and create tag easily. This package works with `bower.json`, `package.json` and `component.json`.

## NPM

If you're using NPM only check [native solution](https://docs.npmjs.com/cli/version)

	npm version [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease]

## Install

	npm install -g version-bump

## Usage

	bump [options]

 * `--patch`, `--minor`, `--major` - Increase specific version
 * `--no-tags` - Do not create git tag
 * `--push` - Push to remote repo

## TODO

 * `--files` get list of manifests for update
 * `--info` shows latest tag and manifests version

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License) (c) Alexey Raspopov
