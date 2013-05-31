npm experiment
==============

Repository to test the if it is possible to install a npm module from
git with a private attribute set.

Resolution
----------

A npm package can only be installed via the `git` protocol. E.g. 

```shell
npm install git://github.com/dvberkel/npm-experiment.git
```

If you want a specific version it should be a tag. E.g

```shell
npm install git://github.com/dvberkel/npm-experiment.git#0.0.0
```
