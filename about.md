---
layout: page
title: About this training
permalink: /about/
---
* TOC
{:toc}

## Training organisation.

Training consists of 3 workshops (each with its own home task) and one optional [warmup][warmup] assignment to check
trainees Symfony framework knowledge level.

[Training schedule][schedule]

## Workshop 1. Architecture of a web project on Symfony.

Bundles organization for a long-term flexibility. Multi-lingual support of static strings and dynamic content.
Example of page with a form: responsibilities of Controller, Service Class, Entity Class, Entity Repository and a Form.
Unit tests to cover important business logic. Example of functional tests environment with fixtures.
How Symfony protects project from such vulnerabilities as XSS, CSRF and SQL Injections.

* Bundles organization
* Multi-lingual support
* Architecture & automation testing
* Custom queries with Doctrine ORM
* Security

## Workshop 2. SonataAdminBundle – CRUD generator for Back-end and Front-end.

Generic controllers of SonataAdmin – you have just configure fields – and CRUD for entity is ready.
Overview of entities with SonataAdminBundle – out of the box we get sortable list with pagination and
configurable filters. Creating forms with SonataAdmin. Deep customization of templates for Front-end. Turning security,
access rights for any operation with content. Adding custom logic into any place of workflow. Uploading files and
images with SonataMedia.

* General abilities
* Usage
* Automation testing for CRUD on SonataAdminBundle
* Customization
* Handling uploads
 

## Workshop 3. High load projects on Symfony.

How to set up application on multiple PHP nodes. Turning performance in Symfony. Architecture for storing
complex logic in SQL queries. Caching queries data. Introduction to HTTP cache.

* Network design
* Framework abilities to increase performance
* Architecture principles & examples
* Cache abilities
* Tips to save memory

[warmup]:       {{ site.baseurl }}{% post_url 2016-04-10-warmup %}
[schedule]:     {{ site.baseurl }}{% post_url 2016-04-10-introduction %}