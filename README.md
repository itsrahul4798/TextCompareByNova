# Text Compare By 😇 Nova

A free, private tool to compare text and code. It works in your browser with no install, no login and no trial.

**Open the app:** https://itsrahul4798.github.io/TextCompareByNova/

## What it does

- Paste old text on the left and new text on the right.
- The app **formats both sides the same way** and then compares them, so different spacing or line breaks don't show up as false differences.
- It shows the result in a simple way:
  - a summary at the top: how many lines changed, were added or were removed, and how similar the two sides are
  - a list of changes, for example `was "West" → now "East"`
  - both sides next to each other, with the changed words marked in red and green

## Supported types

| Type | Formatting |
|---|---|
| DAX | Function names in uppercase, VAR / RETURN on their own lines, long functions split into lines |
| Power Query (M) | `let` steps one per line, long steps split into lines |
| SQL | SELECT / FROM / WHERE / JOIN / CASE on their own lines, keywords in uppercase |
| Python | Tidies spacing and indentation |
| HTML / XML | One tag per line with indentation |
| JSON | Pretty-printed |
| Plain text | Removes spaces at the end of lines |

**Auto detect** picks the type for you. You can also choose it yourself.

## Options

- Ignore case, spaces, blank lines or comments
- Show only differences
- Side-by-side or one-column view
- Jump between differences with Next / Prev (or **Alt + ↓ / ↑**)
- **Ctrl + Enter** to compare
- Load a file with **Open file** or by dragging it onto a box
- Copy the formatted code
- Light and dark mode

## Privacy 🔒

- All formatting and comparing happens **inside your own browser**.
- Your text is **never uploaded or sent anywhere**. The app makes no internet calls.
- Each person's comparisons are visible only to them.
- Your last text and settings are saved only in your own browser. On a shared computer, click **Clear** when you're done.

## Use it offline

Download `index.html` and double-click it. It works with no internet connection.

## How to use

1. Open the app.
2. Paste text in both boxes, or choose an example from **Load example**.
3. Read the summary and the list of changes.


