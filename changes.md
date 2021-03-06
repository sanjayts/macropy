Changelog
=========

1.0.X
-----
- Basic scope analysis now available in the form of the `@Scoped` decorator, to be used in conjunction with `@Walker`.

1.0.3
-----
- Error messages are now raised at run-time rather than at import time, with other improvements (double stack traces, catchability).
- `@enum` macro now has much better error messages
- Improved error messages for mis-use of stub functions outside their related macro (e.g. the `u`, `name`, `ast` stubs for the `q`/`hq` macros)
- Improved error messages for invalid case class signatures
- Hygienic Quasiquotes now allow lexical capture of module objects

1.0.2
-----
- Removed unit test from PyPI distribution

1.0.1
-----
- Fixed a bug in `ast_ctx_fixer`
- `gen_sym()` is now `gen_sym(name="sym")`, allowing you to override the base name
- Implemented `macropy.case_classes.enum` macro
- Implemented `macropy.quick_lambda.lazy` and `macropy.quick_lambda.interned` macros

