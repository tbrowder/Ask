[![Actions Status](https://github.com/tbrowder/Ask/actions/workflows/test.yml/badge.svg)](https://github.com/tbrowder/Ask/actions)

NAME
====

**Ask** - Provides `ask` as an alias for Raku core routine `prompt`

SYNOPSIS
========

```Raku
use Ask;

my $answer = ask "Are you well I hope (Y/n)? ";
if $answer ~~ /:i y/ {
    say "Good, glad to hear it!";
}
else {
    say "Oh, I'm so sorry.";
}
```

DESCRIPTION
===========

This module exports, by `DEFAULT`, `ask` as an alias for the built-in routine `prompt`.

AUTHOR
======

Tom Browder <tbrowder@acm.org>

COPYRIGHT AND LICENSE
=====================

Copyright &#x00A9; 2022 Tom Browder

This library is free software; you can redistribute it or modify it under the Artistic License 2.0.

