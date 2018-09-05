# guld-fs

[![source](https://img.shields.io/badge/source-bitbucket-blue.svg)](https://bitbucket.org/guld/tech-js-node_modules-guld-fs) [![issues](https://img.shields.io/badge/issues-bitbucket-yellow.svg)](https://bitbucket.org/guld/tech-js-node_modules-guld-fs/issues) [![documentation](https://img.shields.io/badge/docs-guld.tech-green.svg)](https://guld.tech/lib/guld-fs.html)

[![node package manager](https://img.shields.io/npm/v/guld-fs.svg)](https://www.npmjs.com/package/guld-fs) [![travis-ci](https://travis-ci.org/guldcoin/tech-js-node_modules-guld-fs.svg)](https://travis-ci.org/guldcoin/tech-js-node_modules-guld-fs?branch=guld) [![lgtm](https://img.shields.io/lgtm/grade/javascript/b/guld/tech-js-node_modules-guld-fs.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/b/guld/tech-js-node_modules-guld-fs/context:javascript) [![david-dm](https://david-dm.org/guldcoin/tech-js-node_modules-guld-fs/status.svg)](https://david-dm.org/guldcoin/tech-js-node_modules-guld-fs) [![david-dm](https://david-dm.org/guldcoin/tech-js-node_modules-guld-fs/dev-status.svg)](https://david-dm.org/guldcoin/tech-js-node_modules-guld-fs?type=dev)

Guld file system abstraction module.

### Install

##### Node

```sh
npm i guld-fs
```

### Usage

```

// must be in an async function.
var fs = await getFS(pify=true) // pify=false to not pify the returned fs
// Now use fs with optional promises and extra functions.
fs.mkdirp('/long/non/existing/path/chain')
fs.cpr('/long/non/existing/path/chain', '/tmp/')
fs.rimraf('/tmp/')
```

### License

MIT Copyright isysd
