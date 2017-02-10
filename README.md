## Requirements

The expirmental StarterKit for Twig requires the following PatternEngine:

* `pattern-lab/patternengine-twig`: [documentation](https://github.com/pattern-lab/patternengine-php-twig#twig-patternengine-for-pattern-lab), [GitHub](https://github.com/pattern-lab/patternengine-php-twig), [Packagist](https://packagist.org/packages/pattern-lab/patternengine-twig)

## Install

This StarterKit can be installed using the following command:

    php core/console --starterkit --install losource/losource-testing-starterkit

Use "r" when prompted to replace the entire source folder if you have already installed a kit in your PatternLab project.

## Setup

First install node packages

    npm install

Install dependencies via bower and build PatternLab with compiled assets for the first time

    npm run build

## Gulp Tasks

To compile all assets and build PL

    Gulp

To watch for changes and serve the compiled /public folder via BrowserSync

    gulp watch

To compile patterns only

    gulp PatternLab


## Edit Files

After installation the files for this StarterKit can be found in `source/`.
