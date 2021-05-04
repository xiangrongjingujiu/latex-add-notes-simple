# add simple note

https://github.com/xiangrongjingujiu/latex-note-plus is too complex, the only need is to add a note of another color and I can hide it quickly

## import package

- use green as color of note, note is shown automatically. ```\usepackage[color=green]{addnote}```，you can use black, blue, brown, cyan, darkgray, gray, green, lightgray, lime, magenta, olive, orange, pink, purple, red, teal, violet, white, yellow
- use green as color of note, note is hided. ```\usepackage[color=green,hide]{addnote}```

## use macro

```\add{note of your own}```

## caveat

- the note is not added to a new line, if you want note to appear on a new line, do it yourself
- do not support complex action, such as new paragraph in note, itemize in note
