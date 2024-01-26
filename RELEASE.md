# Manual update

* Clone project

  `gh repo clone ydb-platform/ydb-nodejs-genproto`

* Bring latest API specification

  `git submodule update --init --recursive`
 
* Rebuild the project:
  
  `npm run build`

* Manually change minor version in *package.json*

* Publish to [npmjs](http://www.npmjs.com). Access is available in the Yandex secrets. Currently maintened by azorkaltsev@yandex-team.com.

  `npm login`

  `npm publish` 
