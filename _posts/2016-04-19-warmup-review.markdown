---
layout: post
title:  "Warmup assignment review"
date:   2016-04-19 09:00:00
category: assignments
tags:
    - training
    - assignment
    - warmup
    - review
excerpt: |
    Recycle batteries.
    Review results. Common mistakes, ideas to improve and notes about this assignment.
---
* TOC
{:toc}

## Received assignments.

* https://github.com/ebessarabov/SymfonyTraining1

* https://github.com/arohachenko/sfdemo_batteries

## Composer.

* You don't need to upload vendor folder. Put it to your ".gitignore" file. Upload only "composer.json" and
   "composer.lock" files

* Add real "name" and "description" fields

* Update/add "php" version in "require" section and used extensions

* Use "github-oauth" token ([details][composer-gh-token])

* Add PHPUnit and similar tools into "composer.json" "require-dev" section

## Git

* Put your local files/folders in ".gitignore" (e.g. ".idea" folder of your IDE)

* Commit often

## Symfony.

* Name your controllers correctly

* Put all bundle related data in bundle itself, ideally they should be independent from each other and from application itself

* Clear all acme demo files 

* Use Symfony IDE integration (e.g PHP Storm [integration][phpstorm-integration])

## Routing.

* Add bundle routes file in app/config/routing only once. Try to avoid route duplication

* If bundle routing is small - use one file

## Forms.

* Do not add submit buttons into form types ([details][sf-forms-buttons])

* Create forms with Symfony 3 approach (e.g. $this->createForm(FormType::class))

* Use @ParamConverter in Controllers ([details][sf-paramconverter])

## Twig.

* Check twig syntax

* Do not use inline JS and CSS

* It's better to use "for ... else" then additional "if" check

## Doctrine.

* Do not use Entity manager if possible

* Try to avoid DQL if possible, use QueryBuilder object

* Use Doctrine entity generator if possible

* Fill all annotations (e.g. primary key autoincrement)

* Use singular for entities and use plural for table names

## Functional tests.

* Tests should be able to run multiple times

* Test functions should be atomic

* It's better to use short selectors

[composer-gh-token]:        https://getcomposer.org/doc/articles/troubleshooting.md#api-rate-limit-and-oauth-tokens
[sf-forms-buttons]:         http://symfony.com/doc/current/best_practices/forms.html#form-button-configuration
[sf-paramconverter]:        http://symfony.com/doc/current/bundles/SensioFrameworkExtraBundle/annotations/converters.html
[phpstorm-integration]:     https://confluence.jetbrains.com/display/PhpStorm/Symfony+Development+using+PhpStorm