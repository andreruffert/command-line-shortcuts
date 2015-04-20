# Command line shortcuts

> Some time-saving bash command line shortcuts for more productivity.


## Directory moving

`cd` (with no arguments) takes you back to your `/~` (home) directory.

`cd -` takes you back to the previous directory you were in.


## Moving the cursor

`<Ctrl-a>` move your cursor to the beginning of the line. Faster than holding down left arrow.

`<Ctrl-e>` move your cursor to the end of the line. Faster than holding down right arrow.


## Editing

`<Ctrl-u>`:  clears the entire line so you can type in a completely new command.

`<Ctrl-k>` deletes the line from the position of the cursor to the end of the line.

`<Ctrl-w>` remove the previous word on the command line (before the cursor). This is highly useful when reusing old commands.

`<Ctrl-l>` clear the Screen, similar to the `clear`. It's usually quicker and doesn't leave the command in your history.


## History:

`<Ctrl-r>string` reverse search through your command history for `string`. Press `<Ctrl-r>` again to continue searching backwards. ESC when done.

`!!` run the last command

`!string` run the most recent command that starts with `string` (e.g. !ls -la)`

`!string:p` Print last command in history beginning with `string` (also adds it as the latest command in the command history)

`<Ctrl-_>` undo
