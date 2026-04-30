# Redline Compare

Redline Compare is a simple browser tool for comparing two versions of the same text.

You can use it here:

https://tzahifadida.github.io/redline-compare/

## What It Is Good For

This is useful when you have a piece of writing and someone, or ChatGPT, gives you a revised version. Instead of reading the whole thing again from the beginning, you can paste the original text on one side, paste the changed text on the other side, and quickly see what changed.

It is especially helpful for:

- Articles
- Academic papers
- Essays
- Grant applications
- Cover letters
- Recommendation letters
- Any short or medium text where small wording changes matter

The tool highlights additions, deletions, and replacements so you can focus only on the changed parts.

## How To Use

1. Open https://tzahifadida.github.io/redline-compare/
2. Paste your original text into the original text box.
3. Paste the revised text into the revised text box.
4. Review the highlighted changes in the document editor.
5. Edit the text directly if you want to make small corrections.
6. Copy the final text when you are done.

## Using With ChatGPT or Other Chat Engines

You can ask ChatGPT, Claude, or another chat engine to return both versions in one copyable block. Then copy that block and click `Import from clipboard`.

Use this prompt:

````
Please present the original text and the revised text in one copyable code block with no language tag, exactly in this format:

```
--- ORIGINAL ---
[the original text]

--- REVISED ---
[the revised text]
```

Do not add anything inside the code block except those two sections.
````

Then:

1. Click the copy button on the chat engine's code block.
2. Open Redline Compare.
3. Click `Import from clipboard`.
4. Review the highlighted changes.

## Keyboard Shortcuts

- Undo: `Cmd+Z` on Mac, `Ctrl+Z` on Windows/Linux
- Redo: `Shift+Cmd+Z` on Mac, `Shift+Ctrl+Z` or `Ctrl+Y` on Windows/Linux
- Copy editor text: `Cmd+C` or `Ctrl+C` when no text is selected
- Next change: `Cmd+Option+Down` on Mac, `Ctrl+Alt+Down` on Windows/Linux
- Previous change: `Cmd+Option+Up` on Mac, `Ctrl+Alt+Up` on Windows/Linux

## Why I Made It

When working on academic writing, I often ask ChatGPT or another editor to improve a paragraph. The result may be better, but it is hard to know exactly what changed without rereading everything carefully.

This tool makes those edits visible. It helps you decide whether to keep a suggested change, revert it, or edit it yourself.

## Privacy

The tool runs entirely in your browser. There is no backend server, no login, and no upload step. The text you paste is processed locally in the page, which helps keep your writing private.

The page may still be served by GitHub Pages, but the comparison itself happens in your browser after the page loads.

## License

This project is released under the Apache 2.0 License. You can read the license here:

https://github.com/tzahifadida/redline-compare/blob/main/LICENSE

## Support

If this tool is useful to you, please consider giving the repository a star on GitHub. It helps other people find it.
