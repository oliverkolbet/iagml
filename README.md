# iagml
It's A Simple Markup Language

Basically translates its own syntax into HTML

## Syntax:

An example of a line:
```iagml
\1`text`This is some text! Yay! EFIHIO#ERFE#"FE#F"Eq#ERFq3uiher1n3iqu
```

Rules:

* Every line must start with a backslash.
* After must come the line number.
* After that comes a backtick, and then the tag.
* After comes some text.
* Some tags require one more backtick, and more text, such as links.

The above example would turn into:
```html
<p>This is some text! Yay! EFIHIO#ERFE#"FE#F"Eq#ERFq3uiher1n3iqu</p>
```

Comments in IAGML are lines starting with #.
