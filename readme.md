## What is this

A simple cjs wrapper to the [@extractus/feed-extractor](https://github.com/extractus/feed-extractor) module

## Why make a wrapper ?

Since version 7, the module [only supports esm import](https://github.com/extractus/feed-extractor/commit/6180e0172c7db9366150689c2f6d75f8695e86f3).
In order to continue using this module conveniently I decided to wrap it in [fix-esm](https://www.npmjs.com/package/fix-esm).

## Why declare @extractus/feed-extractor as a peer dependency ?

Doing this allows you to decide the version in your project.
