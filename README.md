suchchef
========

Opinionated helper script based on Chef Development Kit

Currently only supports OSX.

Uses

* Chef Development Kit
* berkshelf 3 (from CDK)
* test-kitchen (from CDK)
* minitest-handler

Installation
============

Clone the repo and copy the `suchchef` script to somewhere in your PATH

Usage
=====

This will create a cookbook:

    $ suchchef COOKBOOK

You can then go into the cookbook and run the basic tests provided:

    $ cd COOKBOOK
    $ berks install
    $ kitchen test
