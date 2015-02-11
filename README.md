### Introduction

This package may be deprecated. You may now want to take a look at [bobtemplates.plone](https://github.com/plone/bobtemplates.plone)

*bobtemplates.ecreall* provides *mr.bob* templates to generate packages for Plone projects.

This product is freely based on *bobtemplates.niteoweb*.

### Usage

#### Create a mr.bob virtualenv

    mkvirtualenv mrbob

#### Install *mr.bob* and *bobtemplates.ecreall*


    pip install mr.bob
    
    pip install bobtemplates.ecreall

#### Create your package

    mrbob -O collective.foo bobtemplates:plone_addon

See [*mr.bob* documentation](http://mrbob.readthedocs.org/en/latest/) for further information.
