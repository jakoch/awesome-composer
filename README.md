## Awesome Composer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/jakoch/awesome-composer.svg?branch=master)](https://travis-ci.org/jakoch/awesome-composer) [![license](https://img.shields.io/github/license/jakoch/awesome-composer.svg?maxAge=2592000)]()

[<img src="https://raw.githubusercontent.com/jakoch/awesome-composer/master/logo-composer-transparent.png" align="right" width="150">](https://getcomposer.org/)

> A curated list of resources for Composer, Packagist, Satis, Plugins, Scripts, Videos, Tutorials.

You might also like [awesome-php](https://github.com/ziadoz/awesome-php).

*Please read the [contribution guidelines](contributing.md) before contributing.*

## Composer

- [Official Website](https://getcomposer.org/)
- [Issues](https://github.com/composer/composer/issues)
- [Github](https://github.com/composer/composer)
- [Getting Started Guide and Installation Instructions](https://getcomposer.org/doc/00-intro.md)
- [Documentation](https://getcomposer.org/doc/)
- [API Documentation](https://getcomposer.org/apidoc/master/index.html)
- [Find Packages on Packagist](https://packagist.org/)
- [CheatSheet](http://composer.json.jolicode.com/) - Overview of CLI commands and `composer.json` schema.
- [Composer Installers](https://github.com/composer/installers) - Composer installers for multiple frameworks.

### Support

#### Stack Overflow

- You might use the following tags: `composer-php`, `packagist`, `satis` + `php`.
- [Ask a new question](http://stackoverflow.com/questions/ask?tags=composer-php+php)
- [Find questions tagged `composer-php`](http://stackoverflow.com/questions/tagged/composer-php)

#### IRC

- IRC channels are on `irc.freenode.org`: [#composer](https://webchat.freenode.net/?channels=composer) for users and [#composer-dev](https://webchat.freenode.net/?channels=composer-dev) for development.

## Plugins

- [Documentation for Plugins](https://getcomposer.org/doc/articles/plugins.md) - This offical documentation is good starting point, when writing a Composer plugin.
- [Composer-Asset-Plugin](https://github.com/fxpio/composer-asset-plugin) - A npm/Bower Dependencies Manager for Composer.
- [Composer-AWS](https://github.com/naderman/composer-aws) - The plugin loads repository data and downloads packages from Amazon S3 (with authentication support for private repositories).
- [Composer-Composition](https://github.com/bamarni/composition) - Provides an API, for checking your environment at runtime.
- [Composer-Suggest](https://github.com/nfreear/composer-suggest) - Enables you to install a custom group of suggested packages, based on keyword patterns.
- [Climb](https://github.com/deprecat/climb) - Climb is a "Composer version manager tool" inspired by `npm-check-updates`. It shows the outdates package version and indicates "upgrades" to latest versions.
- [Composer-Versions-Check](https://github.com/Soullivaneuh/composer-versions-check) - Shows outdated packages from last major versions after using the update command (showing "Latest is vX.Y.Z").
- [Composer-Changelogs](https://github.com/pyrech/composer-changelogs) - Provides a summary of the updates with links to changelog/releasenote/tag. The output is ready to be pasted into the commit message when updating the composer.lock file.
- [Composer-Merge-Plugin](https://github.com/wikimedia/composer-merge-plugin) - Merges multiple `composer.json` files at Composer runtime.
- [Composer-MonoRepo-Plugin](https://github.com/beberlei/composer-monorepo-plugin) - The plugin adds support for managing dependencies for multiple packages in a single repository.
- [Composer-Patches-Plugin](https://github.com/netresearch/composer-patches-plugin) - Enables you to provide patches for any package from any package. When the dependency is fetched, the patch is applied on top.
- [Composer-Cleanup-Plugin](https://github.com/barryvdh/composer-cleanup-plugin) - Removes tests & documentation folders from the vendor dir.
- [Composer-Cleaner](https://github.com/dg/composer-cleaner) - The tool removes unnecessary files and directories from the vendor directory.
- [Composer-Shared-Package-Plugin](https://github.com/Letudiant/composer-shared-package-plugin) - Allows you to share your selected packages between your projects by creating symlinks.
- [Composer-Symlinker](https://github.com/dg/composer-symlinker) - Enables you to load some packages from different directories (instead of loading them from /vendor).
- [Prestissimo](https://github.com/hirak/prestissimo) - A parallel downloader using `phpext_curl`.
- [Composer-FastFetch](https://github.com/jakoch/composer-fastfetch) - Parallel Downloader using external download tools: Aria2.
- [Composer-Curl-Plugin](https://github.com/ngyuki/composer-curl-plugin) - The plugin use phpext_curl for downloading packages.
- [Composer-Custom-Directory-Installer](https://github.com/mnsami/composer-custom-directory-installer) - A composer plugin, to install different types of composer packages in custom directories outside the default composer installation path (which is in the vendor folder).
- [Composer-Dependency-Analyzer](https://packagist.org/packages/jms/composer-deps-analyzer) - Allows you to build a dependency graph for an installed composer project.
- [PackageVersions](https://github.com/Ocramius/PackageVersions) - Provides a very quick and easy access to installed composer dependency versions.
- [Composer Locator](https://github.com/mindplay-dk/composer-locator) - Provides a means of locating the installation path for a given Composer package name.  
- [PackageInfo](https://github.com/ThaDafinser/PackageInfo) - Check if a package is installed and retrieve all package informations like version, tag release date, description, ... 

## Tools

- [Composer SemVer Checker](https://semver.mwl.be) - Enables you identify constraint to version resolution issues, by doing a semantic version check for Packagist hosted packages.
- [Composer-Yaml](https://github.com/igorw/composer-yaml) - This tool converts composer.yml to composer.json.
- [Studio](https://github.com/franzliedke/studio) - A workbench for developing Composer packages. Its an alternative to editing dependencies in the vendor folder or using [PathRepositories](https://getcomposer.org/doc/05-repositories.md#path) to load a local clone of your dependency into your project.
- [OctoLinker Browser Extension](https://github.com/OctoLinker/browser-extension) - Enables you to navigate Composer/NPM dependencies on Github.

## Scripts

- [ScriptsDev](https://github.com/neronmoon/scriptsdev) - Enables you to use a `scripts-dev` section, which triggers scripts only in dev mode.
- [ParameterHandler](https://github.com/Incenteev/ParameterHandler) - Allows you to manage your ignored parameters when running a composer install or update.
- [PhantomJS-Installer](https://github.com/jakoch/phantomjs-installer)- A Composer Package which installs the PhantomJS binary (Linux, Windows, Mac) into /bin of your project.

## Tutorials 

- [A beginners guide to Composer](https://scotch.io/tutorials/a-beginners-guide-to-composer)
- [A short & simple Composer tutorial](https://www.dev-metal.com/composer-tutorial/)
- [Easy package management with Composer](http://code.tutsplus.com/tutorials/easy-package-management-with-composer--net-25530)
- [PHP Dependency Management with Composer](https://www.sitepoint.com/php-dependency-management-with-composer/)
- [Composer Primer](https://daylerees.com/composer-primer/)
- [PHP Composer Magento Tutorial by Alan Storm](http://alanstorm.com/php_composer_magento_tutorial)

## Slides

- Slides by Nils Aderman
  - [Composer Update](http://www.naderman.de/slippy/src/?file=2015-02-03-Composer-Update.html)
  - [Dependency Management with Composer PHP Reinvented](http://www.naderman.de/slippy/src/?file=2015-02-01-Dependency-Management-with-Composer-PHP-Reinvented.html)
  - [PHP Reinvented - How Composer helped shape the new way of writing PHP](http://www.naderman.de/slippy/src/?file=2014-04-13-PHP-Reinvented.html)
- Slides by Jordi Boggiano
  - [Composer Best Practices](http://slides.seld.be/?file=2015-07-25+Composer+Best+Practices.html)
  - [Introduction to Composer](http://slides.seld.be/?file=2015-06-30+Introduction+to+Composer.html)
  - [In Depth with Composer](http://slides.seld.be/?file=2013-10-05+In-Depth+with+Composer.html)
  - [Dependency Management with Composer](http://slides.seld.be/?file=2013-10-04+Dependency+Management+with+Composer.html)

## Books

- [Creating and Using Composer Packages](https://www.packtpub.com/books/content/creating-and-using-composer-packages)

## Blogs

- [Jordi Boggiano (seldaek)](https://seld.be/)
- [Nils Adermann (naderman)](http://naderman.de/)
- [Composer: Part 1 - What & Why](http://blog.nelm.io/2011/12/composer-part-1-what-why/)
- [Composer: Part 2 - Impact](http://blog.nelm.io/2011/12/composer-part-2-impact/)
- [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html)
- [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html)

## Videos

- [Composer Best Practices — Jordi Boggiano @ php[tek] 2015](https://www.youtube.com/watch?v=uNlYpSTiAcA)
- [Wonderful World of Composer](https://knpuniversity.com/screencast/composer) 
- [PHP Composer Quickstart](https://www.youtube.com/watch?v=Ejr4Xqs9V2I)
- [How Composer helped shape the new way of writing PHP - Nils Adermann @ Drupal Camp Frankfurt](https://www.youtube.com/watch?v=C2jfLM-Egvg)
- [Composer Package Management - Nils Adermann @ T3CON12DE](https://www.youtube.com/watch?v=P4Qnp90TG0g)

## Packagist

- [Packagist-Crawler](https://github.com/hirak/packagist-crawler) - Script to mirror Packagist metadata.

### Packagist Mirrors

- Europe
  - France https://packagist.org/ - 87.98.253.214 (ovh.net).
- Asia
  - Japan http://packagist.jp/ - 104.28.30.100 (CloudFlare, San Fransico, USA).
  - China http://packagist.cn/ - 123.56.107.40 (Aliyun Computing; Alibaba, Hangzhou, China). (Abandoned)
  - China http://www.phpcomposer.com/
- USA
  - Give http://packagist.jp/ a try.

## Satis

- [Gitlab-Composer](https://github.com/wemakecustom/gitlab-composer) - This is a branch/tag indexer for Gitlab repositories.
- [Satisfy](https://github.com/ludofleury/satisfy) - Satis composer repository manager with a Web UI.
- [Satis Control Panel](https://github.com/realshadow/satis-control-panel) - A simple web UI for managing your Satis Repository with optional CI integration.
- [Satis Go](https://github.com/benschw/satis-go) - A web server for managing Satis configuration and hosting the generated Composer repository.

## Proxies

- [ToranProxy](https://toranproxy.com/) - ToranProxy acts as a proxy server for Packagist and GitHub.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jens A. Koch](https://github.com/jakoch) has waived all copyright and related or neighboring rights to this work.
