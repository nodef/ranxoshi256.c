## Documentation

This is a header-only library, as such most of its functional documentation is contained within the "header section" of the
source code in the form of comments. It is highly recommended that you read said documentation before using this library. It was developed by [BareRose](https://github.com/BareRose).

## Installation

Run:
```bash
$ npm i ranxoshi256.c
```

And then include `ranxoshi256.h` as follows:
```c
#include "node_modules/ranxoshi256.c/ranxoshi256.h"
```

## Features

The ranxoshi256 library provides a ready implementation of the xoshiro256** algorithm, its features include:

- No hard dependencies besides the standard library, making it fully portable for most purposes
- Endian-proof seed function to allow for synchronized PRNGs across different machines
- Supports various output functions with different ranges and uniformities

## Attribution

You are not required to give attribution when using this library. If you want to give attribution anyway, either link to
this repository, [my website](https://www.slopegames.com/), or credit me as [BareRose](https://github.com/BareRose).
If you want to support me financially, consider giving to my [Patreon](https://www.patreon.com/slopegames).

## License

Licensed under CC0 aka the most lawyer-friendly way of spelling "public domain".

<br>
<br>


[![ORG](https://img.shields.io/badge/org-nodef-green?logo=Org)](https://nodef.github.io)
![](https://ga-beacon.deno.dev/G-RC63DPBH3P:SH3Eq-NoQ9mwgYeHWxu7cw/github.com/nodef/ranxoshi256.c)
[![SRC](https://img.shields.io/badge/src-repo-green?logo=Org)](https://github.com/BareRose/ranxoshi256)
