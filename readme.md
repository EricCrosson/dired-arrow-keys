# dired-arrow-keys [![Build Status](https://travis-ci.org/EricCrosson/dired-arrow-keys.svg?branch=master)](https://travis-ci.org/EricCrosson/dired-arrow-keys)
[![Version](https://img.shields.io/github/tag/EricCrosson/dired-arrow-keys.svg)](https://github.com/EricCrosson/dired-arrow-keys/releases)

> Navigate Dired buffers with the arrow keys

Map

| Key                | Bound function                |
|--------------------|-------------------------------|
| <kbd><right></kbd> | `dired-find-file`             |
| <kbd><left></kbd>  | `dired-find-parent-directory` |

And for [evil](https://github.com/emacs-evil/evil) users,

| Key                | Bound function                |
|--------------------|-------------------------------|
| <kbd>h</kbd>       | `dired-find-file`             |
| <kbd>l</kbd>       | `dired-find-parent-directory` |

## Install

With [Quelpa](https://framagit.org/steckerhalter/quelpa)

``` {.sourceCode .lisp}
(use-package dired-arrow-keys
  :quelpa (dired-arrow-keys
           :fetcher github
           :repo "EricCrosson/dired-arrow-keys")
  :config (dired-arrow-keys-install))
```

Or manually, after downloading into your `load-path`

``` {.sourceCode .lisp}
(require 'dired-arrow-keys)
(dired-arrow-keys-install)
```

## License

GPL 2 (or higher) © [Free Software Foundation, Inc](http://www.fsf.org/about).
