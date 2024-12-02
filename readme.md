# Node.JS (& Typescript) PST API

[![npm](https://img.shields.io/npm/v/pst-extractor.svg)](https://www.npmjs.com/package/pst-extractor) ![github-issues](https://img.shields.io/github/issues/epfromer/pst-extractor.svg) ![stars](https://img.shields.io/github/stars/epfromer/pst-extractor.svg) ![forks](https://img.shields.io/github/forks/epfromer/pst-extractor.svg) ![](https://david-dm.org/epfromer/pst-extractor/status.svg) ![](https://david-dm.org/epfromer/pst-extractor/dev-status.svg) [![codecov](https://codecov.io/gh/epfromer/pst-extractor/branch/master/graph/badge.svg)](https://codecov.io/gh/epfromer/pst-extractor)

Extract objects from MS Outlook/Exchange PST files

## Features

Extract objects from MS Outlook/Exchange PST files.

This is based off code from https://github.com/rjohnsondev/java-libpst. Thanks to Richard Johnson and Orin Eman.

A spec from Microsoft on the PST file format is at https://msdn.microsoft.com/en-us/library/ff385210(v=office.12).aspx.

## Install

```npm install --save pst-extractor```

or

```yarn add pst-extractor```

## Usage

Start with the example app to walk the PST and print out the folder structure to the console. Also, most of the major objects have Jest test specs which show how the object attributes can be accessed.

```bash
cd example
npm start
```

or

```bash
cd example
yarn start
```