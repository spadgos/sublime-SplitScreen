SplitScreen is a [Sublime Text 2][sublime] plugin which allows you to define custom ratios for split screen editing.

---

By default, Sublime has some predefined split-window configuration, accessible via the <kbd>Alt+Shift+&lt;number&gt;</kbd> hotkeys, however, if you want something other than these presets, it is quite difficult to create your own. Enter SplitScreen!

1. To activate, press the hotkey, <kbd>Alt+Shift+S</kbd>, and an input box will appear at the bottom of the screen.

2. Enter some ratios, horizontal (columns) first, and then vertical (rows) second. Numbers are treated as a ratio, so `50:50` is identical to `1:1`. Separate columns and rows with a comma. If you want only one row or column, then that can be left blank.

For example:


    50:50
    (2 columns, equal width. 1 row)

    --------------------
    |        |         |
    |        |         |
    |        |         |
    |        |         |
    |        |         |
    |        |         |
    --------------------

    1:2
    (2 columns, one twice the width of the other. 1 row)

    --------------------
    |      |           |
    |      |           |
    |      |           |
    |      |           |
    |      |           |
    --------------------

    ,1:1
    (1 column, two rows equal width)

    --------------------
    |                  |
    |                  |
    --------------------
    |                  |
    |                  |
    --------------------

    70:30,2:1
    (2 columns, 2 rows)

    --------------------
    |             |    |
    |             |    |
    |             |    |
    |             |    |
    --------------------
    |             |    |
    |             |    |
    --------------------

**Tip**: To go back to just one window, you can enter an empty string, or a single number, or simply use the built-in hotkey <kbd>Alt+Shift+1</kbd>.

[sublime]: http://www.sublimetext.com/
