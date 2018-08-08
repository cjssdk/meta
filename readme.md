CJS SDK management
==================

## Usage ##

Install global dependencies:

```bash
sudo npm install -g meta
```

Get meta repo:

```bash
git clone https://github.com/cjssdk/meta.git cjssdk
# or for Github users with granted access
git clone git@github.com:cjssdk/meta.git cjssdk
cd cjssdk
```

All preparations:

```bash
npm install
meta git update
meta npm install
sudo meta npm link --all
```


## Packages ##

 Repo                                                                  | Build status                                                                                                                                  | NPM version                                                                                                                                   | Dependencies status                                                                                                                                | devDependencies status
-----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|------------------------
[cjs-async](https://github.com/cjssdk/async.git)                       | [![build status](https://img.shields.io/travis/cjssdk/async.svg?style=flat-square)](https://travis-ci.org/cjssdk/async)                       | [![npm version](https://img.shields.io/npm/v/cjs-async.svg?style=flat-square)](https://www.npmjs.com/package/cjs-async)                       | [![dependencies status](https://img.shields.io/david/cjssdk/async.svg?style=flat-square)](https://david-dm.org/cjssdk/async)                       | [![dependencies status](https://img.shields.io/david/dev/cjssdk/async.svg?style=flat-square)](https://david-dm.org/cjssdk/async?type=dev)
[cjs-emitter](https://github.com/cjssdk/emitter.git)                   | [![build status](https://img.shields.io/travis/cjssdk/emitter.svg?style=flat-square)](https://travis-ci.org/cjssdk/emitter)                   | [![npm version](https://img.shields.io/npm/v/cjs-emitter.svg?style=flat-square)](https://www.npmjs.com/package/cjs-emitter)                   | [![dependencies status](https://img.shields.io/david/cjssdk/emitter.svg?style=flat-square)](https://david-dm.org/cjssdk/emitter)                   | [![dependencies status](https://img.shields.io/david/dev/cjssdk/emitter.svg?style=flat-square)](https://david-dm.org/cjssdk/emitter?type=dev)
[cjs-eslint](https://github.com/cjssdk/eslint.git)                     | (n/a)                                                                                                                                         | [![npm version](https://img.shields.io/npm/v/cjs-eslint.svg?style=flat-square)](https://www.npmjs.com/package/cjs-eslint)                     | [![dependencies status](https://img.shields.io/david/cjssdk/eslint.svg?style=flat-square)](https://david-dm.org/cjssdk/eslint)                     | [![dependencies status](https://img.shields.io/david/dev/cjssdk/eslint.svg?style=flat-square)](https://david-dm.org/cjssdk/eslint?type=dev)
[cjs-format](https://github.com/cjssdk/format.git)                     | [![build status](https://img.shields.io/travis/cjssdk/format.svg?style=flat-square)](https://travis-ci.org/cjssdk/format)                     | [![npm version](https://img.shields.io/npm/v/cjs-format.svg?style=flat-square)](https://www.npmjs.com/package/cjs-format)                     | [![dependencies status](https://img.shields.io/david/cjssdk/format.svg?style=flat-square)](https://david-dm.org/cjssdk/format)                     | [![dependencies status](https://img.shields.io/david/dev/cjssdk/format.svg?style=flat-square)](https://david-dm.org/cjssdk/format?type=dev)
[cjs-gettext](https://github.com/cjssdk/gettext.git)                   | [![build status](https://img.shields.io/travis/cjssdk/gettext.svg?style=flat-square)](https://travis-ci.org/cjssdk/gettext)                   | [![npm version](https://img.shields.io/npm/v/cjs-gettext.svg?style=flat-square)](https://www.npmjs.com/package/cjs-gettext)                   | [![dependencies status](https://img.shields.io/david/cjssdk/gettext.svg?style=flat-square)](https://david-dm.org/cjssdk/gettext)                   | [![dependencies status](https://img.shields.io/david/dev/cjssdk/gettext.svg?style=flat-square)](https://david-dm.org/cjssdk/gettext?type=dev)
[cjs-iso-639](https://github.com/cjssdk/iso-639.git)                   | [![build status](https://img.shields.io/travis/cjssdk/iso-639.svg?style=flat-square)](https://travis-ci.org/cjssdk/iso-639)                   | [![npm version](https://img.shields.io/npm/v/cjs-iso-639.svg?style=flat-square)](https://www.npmjs.com/package/cjs-iso-639)                   | [![dependencies status](https://img.shields.io/david/cjssdk/iso-639.svg?style=flat-square)](https://david-dm.org/cjssdk/iso-639)                   | [![dependencies status](https://img.shields.io/david/dev/cjssdk/iso-639.svg?style=flat-square)](https://david-dm.org/cjssdk/iso-639?type=dev)
[cjs-property-watcher](https://github.com/cjssdk/property-watcher.git) | [![build status](https://img.shields.io/travis/cjssdk/property-watcher.svg?style=flat-square)](https://travis-ci.org/cjssdk/property-watcher) | [![npm version](https://img.shields.io/npm/v/cjs-property-watcher.svg?style=flat-square)](https://www.npmjs.com/package/cjs-property-watcher) | [![dependencies status](https://img.shields.io/david/cjssdk/property-watcher.svg?style=flat-square)](https://david-dm.org/cjssdk/property-watcher) | [![dependencies status](https://img.shields.io/david/dev/cjssdk/property-watcher.svg?style=flat-square)](https://david-dm.org/cjssdk/property-watcher?type=dev)
[cjs-query](https://github.com/cjssdk/query.git)                       | [![build status](https://img.shields.io/travis/cjssdk/query.svg?style=flat-square)](https://travis-ci.org/cjssdk/query)                       | [![npm version](https://img.shields.io/npm/v/cjs-query.svg?style=flat-square)](https://www.npmjs.com/package/cjs-query)                       | [![dependencies status](https://img.shields.io/david/cjssdk/query.svg?style=flat-square)](https://david-dm.org/cjssdk/query)                       | [![dependencies status](https://img.shields.io/david/dev/cjssdk/query.svg?style=flat-square)](https://david-dm.org/cjssdk/query?type=dev)
[cjs-runner](https://github.com/cjssdk/runner.git)                     | [![build status](https://img.shields.io/travis/cjssdk/runner.svg?style=flat-square)](https://travis-ci.org/cjssdk/runner)                     | [![npm version](https://img.shields.io/npm/v/cjs-runner.svg?style=flat-square)](https://www.npmjs.com/package/cjs-runner)                     | [![dependencies status](https://img.shields.io/david/cjssdk/runner.svg?style=flat-square)](https://david-dm.org/cjssdk/runner)                     | [![dependencies status](https://img.shields.io/david/dev/cjssdk/runner.svg?style=flat-square)](https://david-dm.org/cjssdk/runner?type=dev)
[cjs-uri](https://github.com/cjssdk/uri.git)                           | [![build status](https://img.shields.io/travis/cjssdk/uri.svg?style=flat-square)](https://travis-ci.org/cjssdk/uri)                           | [![npm version](https://img.shields.io/npm/v/cjs-uri.svg?style=flat-square)](https://www.npmjs.com/package/cjs-uri)                           | [![dependencies status](https://img.shields.io/david/cjssdk/uri.svg?style=flat-square)](https://david-dm.org/cjssdk/uri)                           | [![dependencies status](https://img.shields.io/david/dev/cjssdk/uri.svg?style=flat-square)](https://david-dm.org/cjssdk/uri?type=dev)
[cjs-wamp](https://github.com/cjssdk/wamp.git)                         | [![build status](https://img.shields.io/travis/cjssdk/wamp.svg?style=flat-square)](https://travis-ci.org/cjssdk/wamp)                         | [![npm version](https://img.shields.io/npm/v/cjs-wamp.svg?style=flat-square)](https://www.npmjs.com/package/cjs-wamp)                         | [![dependencies status](https://img.shields.io/david/cjssdk/wamp.svg?style=flat-square)](https://david-dm.org/cjssdk/wamp)                         | [![dependencies status](https://img.shields.io/david/dev/cjssdk/wamp.svg?style=flat-square)](https://david-dm.org/cjssdk/wamp?type=dev)


## Contribution ##

If you have any problems or suggestions please open an [issue](https://github.com/cjssdk/meta/issues)
according to the contribution [rules](.github/contributing.md).


## License ##

`@cjssdk/meta` is released under the [GPL-3.0 License](http://opensource.org/licenses/GPL-3.0).
