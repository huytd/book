# The Rust Programming Language Book

## Requirements

Building book require [mdBook](https://github.com/azerupi/mdBook) >= v0.0.13. To
get it:

```
cargo install mdbook
```

## Building

```
mdbook build
```

The output will be in the book directory. To check it out, open it in your
browser:

```
open -a "Firefox" book/index.html # OS X
```

```
open -a "Google Chrome" book/index.html # OS X
```

To run the tests:

```
mdbook test
```
