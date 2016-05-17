---
layout: post
title:  "Assignment 3 review. Students database"
date:   2016-05-17 09:00:00
category: assignments
tags:
    - training
    - assignment
    - students database
    - review
excerpt: |
    Students database.
    Review results. Common mistakes, ideas to improve and notes about this assignment.
---
* TOC
{:toc}

## Received assignments.

* https://github.com/ebessarabov/students-database

* https://github.com/Avariya/studentsDatabase

* https://github.com/arohachenko/sfdemo_students

* https://github.com/mountine-orc/students

* https://github.com/myroshnychenko/students_db

## PHP.

* Garbage collector

## Symfony.

* No need to use all standard bundles. Just disable them and some memory & CPU time

* Try to decouple your services

* Pass as more specific classes as possible as dependencies into your services

* Check for new Symfony micro framework feature [Symfony MicroKernelTrait][symfony-microkerneltrait]

## Doctrine.

* Put your custom queries into repository classes

## Unit tests.

* Use @dataproviders

* Test all possible input chars in unit tests

* It's ok to use negative test cases

[symfony-microkerneltrait]: http://symfony.com/doc/current/cookbook/configuration/micro-kernel-trait.html