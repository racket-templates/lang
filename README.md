# `#lang` template

A template for a `#lang` language

# How To Install

1. [Set your PATH environment variable](https://github.com/racket/racket/wiki/Set-your-PATH-environment-variable) 
so you can use `raco` and other Racket command line functions.
2. either look for `from-template` in the DrRacket menu **File|Package Manager**, or run the `raco` command:
```bash
raco pkg install from-template
```
3. 
```bash
raco new lang <destination-dir>
```
If you omit `<destination-dir>`, the command will add copy the template to a folder called `lang` in the current folder.

# How to use

This is working example that you can change to suit your needs.

See https://github.com/racket/racket/wiki/Creating-Languages for resources on creating languages.

# Description

This template is derived from https://github.com/samth/xlang : 

A language of combinators and numeric constants, implemented in Racket.

Examples:
```
#lang xlang
(S K I X)
```

```
#lang xlang
(K 1 2)

To Install: `raco pkg install xlang`

To learn about combinators: http://en.wikipedia.org/wiki/Combinatory_logic

