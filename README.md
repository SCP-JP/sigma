## Sigma-10

[![Lint](https://github.com/SCP-JP/sigma/actions/workflows/lint.yaml/badge.svg)](https://github.com/SCP-JP/sigma/actions/workflows/lint.yaml)

This is the repository for the [Sigma-10 theme (Localized for JP)](https://scp-jp.wikidot.com/theme:site), the default CSS used to style the [JP SCP Wiki](https://scp-jp.wikidot.com). It was originally created by the [EN SCP Wiki Technical Team](https://github.com/scpwiki) and [Aelanna](https://www.wikidot.com/user:info/aelanna) under the name Sigma-9 and is presently maintained by the JP SCP Wiki Technical Team.

This theme is available under the wiki's [Creative Commons Attribution-ShareAlike 3.0 license (CC-BY-SA)](https://creativecommons.org/licenses/by-sa/3.0/).

Upon merging or pushing to the `main` branch, CSS will be deployed to [GitHub Pages](https://scp-jp.github.io/sigma/) so the artifacts can be used by the theme in production.

### Local development

Be sure you have `npm` installed, and then set up the development dependencies:

```
$ npm install
```

Once this is configured, there are a few scripts you can take advantage of:

```
$ npm run build         # Builds the theme and outputs to dist/
$ npm run clean         # Deletes dist/
$ npm run stylelint     # Runs stylelint, reporting any code issues
$ npm run stylelint:fix # Runs stylelint, automatically fixing issues
$ npm run prettier      # Runs prettier, reporting any formatting issues
$ npm run prettier:fix  # Runs prettier, automatically fixing issues
$ npm run minify        # Minifies sigma.css and places it into dist/
```
