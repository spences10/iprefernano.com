# I Prefer GNU nano

As a developer there will come a time when you have to SSH onto a
server to do some file edits. It's at these times when you're reminded
of the existence of command line text editors.

## Opening and Creating Files

```bash
nano new-file
```

This will open or create the `new-file` you can then edit to your
hearts content, or to get the job done!

All the commands in the editor are prefixed with `^` or `M` the caret
symbol (`^`) is the `Crtl` key and the `M` is for the `Alt` key (so
intuitive!).

You can get a list of all available commands by using `Ctrl+g`.

You can open files with the cursor in a specified position, to open a
file on line 3 character 5 of the file:

```bash
nano +3,5 new-file
```

## Editing Files

Unlike Vim nano doesn't have modes which means you don't need to `Esc`
and `:q!` to exit, with intuitive navigation around a document. i.e.
move the cursor with the arrow keys.

## Resources

nano docs: https://www.nano-editor.org/
