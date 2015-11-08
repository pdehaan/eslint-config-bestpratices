eslint-config-bestpratices
==========================

eslint [Best Pratices](http://eslint.org/docs/rules/#best-practices) rules enabled

[![build status](https://img.shields.io/travis/sonnyp/eslint-config-bestpratices/master.svg?style=flat-square)](https://travis-ci.org/sonnyp/eslint-config-bestpratices/branches)

This [eslint](http://eslint.org/) config provides all eslint [Best Pratices](http://eslint.org/docs/rules/#best-practices) rules enabled out of the box.

### Usage

```
npm install eslint eslint-config-bestpratices --save
```

and extend this configuration, see [Extending Configuration Files](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) eslint documentation.

### Examples

JSON .eslintrc

```
{
  extends: [
    'bestpratices'
  ]
}
```

YAML .eslintrc

```
extends:
  - 'bestpratices'
```
