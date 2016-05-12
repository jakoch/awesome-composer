## Awesome Composer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/jakoch/awesome-composer.svg?branch=master)](https://travis-ci.org/jakoch/awesome-composer)

A curated awesome list for Composer, Packagist, Satis, Plugins, Scripts, Composer related resources, tutorials.

Inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

License: [Public Domain](http://creativecommons.org/publicdomain/zero/1.0/)

## Composer

- [Official Website](https://getcomposer.org/)
- [Issues](https://github.com/composer/composer/issues)
- [Github](https://github.com/composer/composer)
- [Getting Started Guide and Installation Instructions](https://getcomposer.org/doc/00-intro.md)
- [Documentation](https://getcomposer.org/doc/)
- [API Documentation](https://getcomposer.org/apidoc/master/index.html)
- [Find Packages on Packagist](https://packagist.org/)
- [CheatSheet](http://composer.json.jolicode.com/) - Overview of CLI commands and `composer.json` schema
- [Composer Installers](https://github.com/composer/installers) - Composer installers for multiple frameworks.

### Support

#### StackOverflow

- You might use the following tags: `composer-php`, `packagist`, `satis` + `php`.
- [Ask a new question](http://stackoverflow.com/questions/ask?tags=composer-php+php)
- [Find questions tagged `composer-php`](http://stackoverflow.com/questions/tagged/composer-php)

#### IRC

- IRC channels are on `irc.freenode.org`: `#composer` for users and `#composer-dev` for development.

## Plugins

- [Documentation for Plugins](https://getcomposer.org/doc/articles/plugins.md)

- [Composer-Asset-Plugin](https://github.com/francoispluchino/composer-asset-plugin)
  - A NPM/Bower Dependencies Manager for Composer
- [Composer-AWS](https://github.com/naderman/composer-aws)
  - The plugin loads repository data and downloads packages from Amazon S3 (with authentication support for private repositories).
- [Composer-Composition](https://github.com/bamarni/composition)
- [Composer-Suggest](https://github.com/nfreear/composer-suggest)
  - A Composer plugin to install a custom group of suggested packages, based on keyword patterns.
- [Climb](https://github.com/deprecat/climb)
  -  Climb is a "Composer version manager tool" inspired by npm-check-updates. It shows the outdates package version and indicates "upgrades" to latest versions.
- [Composer-Versions-Check](https://github.com/Soullivaneuh/composer-versions-check)
  - The Composer Plugin called "composer-versions-check" shows outdated packages from last major versions after using the update command. (Showing "Latest is vX.Y.Z")
- [Composer-Changelogs](https://github.com/pyrech/composer-changelogs)
  - It provides a summary of the updates with links to changelog/releasenote/tag. The output is ready to be pasted into the commit message when updating the composer.lock file.
- [Composer-Merge-Plugin](https://github.com/wikimedia/composer-merge-plugin)
  - Merges multiple `composer.json` files at Composer runtime.
- [Composer-Patches-Plugin](https://github.com/netresearch/composer-patches-plugin)
  - This plugin allows you to provide patches for any package from any package. When the dependency is fetched, the patch is applied on top.
- [Composer-Cleanup-Plugin](https://github.com/barryvdh/composer-cleanup-plugin)
  - Remove tests & documentation folders from the vendor dir.
- [Composer-Cleaner](https://github.com/dg/composer-cleaner)
  - This tool removes unnecessary files and directories from the vendor directory.
- [Composer-Shared-Package-Plugin](https://github.com/Letudiant/composer-shared-package-plugin)
  - This composer plugin allows you to share your selected packages between your projects by creating symlinks.
- [Composer-Symlinker](https://github.com/dg/composer-symlinker)
  - This tool forces the Composer to load some packages from different directories (instead of loading them from /vendor).
- [Prestissimo](https://github.com/hirak/prestissimo)
  - Parallel Downloader using phpext_curl
- [Composer-FastFetch](https://github.com/jakoch/composer-fastfetch)
  - Parallel Downloader using external download tools: Aria2
- [Composer-Curl-Plugin](https://github.com/ngyuki/composer-curl-plugin)
  - The plugin use phpext_curl for downloading packages.
- [Composer-Custom-Directory-Installer](https://github.com/mnsami/composer-custom-directory-installer)
  - A composer plugin, to install different types of composer packages in custom directories outside the default composer installation path (which is in the vendor folder).
- [Composer-Dependency-Analyzer](https://packagist.org/packages/jms/composer-deps-analyzer)
  - This library allows you to build a dependency graph for an installed composer project.
- [PackageVersions](https://github.com/Ocramius/PackageVersions)
  - This utility provides very quick and easy access to installed composer dependency versions.
- [Composer Locator](https://github.com/mindplay-dk/composer-locator)
  - This Composer plugin provides a means of locating the installation path for a given Composer package name.  

## Tools

- [Composer-Yaml](https://github.com/igorw/composer-yaml)
  - This tool converts composer.yml to composer.json.
- [Studio](https://github.com/franzliedke/studio)
  - A workbench for developing Composer packages. Its an alternative to editing dependencies in the vendor folder or using [PathRepositories](https://getcomposer.org/doc/05-repositories.md#path) to load a local clone of your dependency into your project.

## Scripts

- [ParameterHandler](https://github.com/Incenteev/ParameterHandler)
  - This script allows you to manage your ignored parameters when running a composer install or update.
- [PhantomJS-Installer](https://github.com/jakoch/phantomjs-installer)
  - A Composer Package which installs the PhantomJS binary (Linux, Windows, Mac) into /bin of your project.

## Packagist

- [Packagist-Crawler](https://github.com/hirak/packagist-crawler) - Script to mirror Packagist metadata

### Packagist Mirrors

- Europe
  - France https://packagist.org/ - 87.98.253.214 (ovh.net)
- Asia
  - Japan http://packagist.jp/ - 104.28.30.100 (CloudFlare, San Fransico, USA)
  - China http://packagist.cn/ - 123.56.107.40 (Aliyun Computing; Alibaba, Hangzhou, China)
- USA
  - give http://packagist.jp/ a try

## Satis

- [Gitlab-Composer](https://github.com/wemakecustom/gitlab-composer) - This is a branch/tag indexer for Gitlab repositories.
- [Satisfy](https://github.com/ludofleury/satisfy) - Satis composer repository manager with a Web UI.
- [Satis Control Panel](https://github.com/realshadow/satis-control-panel) - Is a simple web UI for managing your Satis Repository for Composer Packages.
- [Satis Go](https://github.com/benschw/satis-go) - Satis-go is a web server for hosting and managing your Satis Repository for Composer Packages.

## Proxies

- [ToranProxy](https://toranproxy.com/) - ToranProxy acts as a proxy server for Packagist and GitHub
