# bfwg
bfwg is a extension of brainf\*\*k with only ONE more command: `!`. That single command enables **graphics**.

## Wait.. WHAT?
Yes, you heard me correctly. **One** command enables graphics. How it works is that the cell you run it on acts as the *command*, and the cell(s) after it acts as the *argument(s)*. Some commands also return things in the argument space after running. Here are are the commands (along with the arguments you need for them):

| Command number | Description | Argument(s) | Returns(s) |
| -------------- | ----------- | ----------- | ---------- |
| 0x00 (0) TODO  | Creates a window with the specfied title, width, and height. | Width, Height, Title length, Title | Window ID, Failed (inverse, so you can easily detect it with []) |
| 0x01 (1) TODO  | Set the render window to an Window ID. | Window ID | (none) |
| 0x02 (2) TODO  | Sets the current render color. | Red, Green, Blue | (none) |
| 0x03 (3) TODO  | Clears the screen, with the current render color. | (none) | (none)
| 0x04 (4) TODO  | Draws a line, with the current render color. | From X, From Y, To X, To Y | (none)

## Okay... how do I run it?
So just install Python and run main.py.