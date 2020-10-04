# Template Literal querySelector

Type declaration wrapper for, and extension of an [early implementation][playground] of extended template literal type inferrence for `querySelector` posted by Oorta in [microsoft/TypeScript#29037][issue]. 

![][ex01]

In addition to `ParentNode#querySelector`, `ParentNode#querySelectorAll` is extended and returns an appropirately narrowed `HTMLCollection` (`HTMLCollectionOf`).

This is intended to be an interim solution; the library implementation should be used when added.

## Install

``` shell
npm install --save-dev "http://github.com/disco0/template-literal-queryselectors/tarball/main"
```

## Usage

In `globals.d.ts`, or each JavaScript / TypeScript file:

``` ts
///<reference types="template-literal-queryselectors"/>
```


[playground]: https://tsplay.dev/BmxabW
[issue]: https://github.com/microsoft/TypeScript/issues/29037

[ex01]: ./media/example-01.png
