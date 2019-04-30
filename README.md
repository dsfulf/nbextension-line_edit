# Line Edit

Jupyter Notebook commands to duplicate a line, and delete a line. CodeMirror script taken from [here](http://stackoverflow.com/a/40505055/6003870). Keyboard shortcuts chosen for similarity with Sublime Text and Atom (note that `Ctrl-Shift-D` is a browser shortcut to bookmark a page and cannot be used).

- *Ctrl+Alt+D* : duplicate line
- *Ctrl+Alt+K* : delete line

___

To install:

```
git clone https://github.com/dsfulf/nbextension-line_edit
jupyter nbextension install nbextension-line_edit
```

Enable the extension (optional, you can instead use the `nbextension` tab in Jupyter Notebook):

```
jupyter nbextension enable nbextension-line_edit/main
```

To disable the extension:

```
jupyter nbextension disable nbextension-line_edit/main
```
