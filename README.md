# dokupruned DokuWiki template

Pruned DokuWiki template based on the default DokuWiki template
([template:dokuwiki](https://www.dokuwiki.org/template:dokuwiki))
by [Anika Henke](http://blog.selfthinker.org/)

"Fork" of [splitbrain/dokuwiki/tree/stable/lib/tpl/dokuwiki](https://github.com/splitbrain/dokuwiki/tree/stable/lib/tpl/dokuwiki)
via `git subtree split`

Install by extracting contents of this repo to `lib/tpl/dokupruned` under your
DokuWiki root, then in Configuration Manager set template to dokupruned.

## Changelog

### [dokupruned-2017-02-17e.1] - 2018-02-01

- removed "Register" links/entries from header to allow
  [plugin:oauth](https://www.dokuwiki.org/plugin:oauth) to register new OAuth
  users while removing built-in registration from navigation
  - see cosmocode/dokuwiki-plugin-oauth#62
- removed badges from footer except for license and DokuWiki badges

[dokupruned-2017-02-17e.1]: https://github.com/mhenry07/dokuwiki-template-dokupruned/compare/dokuwiki-template-2017-02-19e...dokupruned-2017-02-19.1
