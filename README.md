# generator-hypress (v0.0.1)
![Version](https://img.shields.io/badge/version-v0.0.1-violet.svg)
![Last commit](https://img.shields.io/github/last-commit/hypress/generator-hypress.svg?style=flat)
![Build status](https://api.travis-ci.org/hypress/generator-hypress.svg?branch=develop)

A [yeoman] generator to create a [hypress] project.

## Installation
Install yeoman and this generator:

```bash
npm install -g yo
npm install generator-hypress
```

## Usage
Create a project by running the hypress generator:

```bash
yo hypress
```

… done.

## Contributing
This projects is open for contributions.

### Update skeleton
To update the embeded skeleton, run the update script:

```bash
npm run update-skeleton
```

This copies the latest skeleton files to the app generator template folder. 
You need to adjust the following files with 
`<%= projectSlug %>` and `<%= projectName %>`. 

- `README.md`
- `Vagrantfile`
- `generators/app/templates/composer.json`
- `generators/app/templates/package.json`
- `generators/app/templates/.hypress/ansible/settings.yml`



[hypress]: https://github.com/hypress
[yeoman]: https://yeoman.io/
