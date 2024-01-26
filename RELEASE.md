# Manual update

## Get project from git

* clone project

  `gh repo clone ydb-platform/ydb-nodejs-genproto`

* bring latest API specification

  `git submodule update --init --recursive`
 
## When project already is on the local drive

* Update project code with latest API spec (submodules)

  `git submodule update --init --recursive`

* Rebuild the project:
  
  `npm run build`

* Manually change package version in package.json

* Publish to npmjs.com (Access is available in the Yandex secrets.  Currently maintened by azorkaltsev@yandex-team.com):

  `npm login`

  `npm publish` 
