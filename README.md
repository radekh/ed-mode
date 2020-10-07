# ed for Emacs
ed-mode lets you interact with Emacs buffers like you would do with
the ed editor.

## Installation
```
(use-package ed
    :straight (ed
		  :type git
		  :host github
		  :repo "radekh/ed-mode"
		  :files ("ed.el")))
```

## Usage
Use ed by opening a file like you’d normally do, and then do:
<kbd>M‑x</kbd> ed <kbd>RET</kbd>
