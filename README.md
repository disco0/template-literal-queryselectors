# Template Literal querySelector

Type declaration wrapper for, and extension of an [early implementation][playground] of extended template literal type inferrence for `querySelector` posted by Oorta in [microsoft/TypeScript#29037][issue]. 

![][ex01]

In addition to `ParentNode#querySelector`, `ParentNode#querySelectorAll` is extended and returns an appropirately narrowed `HTMLCollection` (`HTMLCollectionOf`).

This is intended to be an interim solution; the library implementation should be used when added.

[playground]: https://tsplay.dev/BmxabW
[issue]: https://github.com/microsoft/TypeScript/issues/29037

[ex01]: ./media/example-01.png
