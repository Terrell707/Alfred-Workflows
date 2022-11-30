# Alfred-Workflows

My collection of Workflows used created for Alfred

## Move Files/Folders

[Download - Move Files/Folders]

Moves the specified files/folders to the configured "Destination" path. Also have the option to overwrite existing files/folders.

This workflow can be triggered using:
• File Actions
• File Buffers
• Hotkey
• Keyword

By setting up a hotkey in Alfred to use File Actions, or Universal Actions, you can action one or more files and run the "Move Files Workflow" item to immediately move the items.
Can also invoke the workflow by using the "move" keyword. This will give you three choices:

### File Filter

Search files by typing search words after the keyword. Once you see the item you want to move, simply action the result. The window will stay open so you can continue to move files if needed.

### File Buffer

Simply add files to the File Buffer using Alfred, then action the buffer using the "Move Files Workflow" item. All items in the buffer will be moved and the buffer will be cleared.

### Selected Paths in Finder

While Finder is open, simply make sure the item you want to move is selected, then action this result. The workflow will find the selected item in Finder and move it to the destination. You can also select multiple items in Finder by using `Command+Click` the mouse to select multiple items and then action this result.

Optionally, you can set hotkeys in the workflow to each of the above items.

[download - move files/folders]: https://github.com/Terrell707/Alfred-Workflows/raw/main/workflows/Move%20Files:Folders.alfredworkflow

## Pocket

Pocket is a workflow that makes moving and actioning files a breeze, no matter how many files you're dealing with and where they're located.

To get started, set a hotkey to store your items. The workflow also has a file action configured so you can simply use the power of Alfred's File/Universal Actions and simply select "Pocket Files/Folders".

You will also need a hotkey for moving the currently pocketed files/folders to the frontmost Finder path, and/or a hotkey to action the items in Alfred. When you're ready to action these files, simply press the hotkey you configured.

### Changelog

#### 1.1.0

-   Added keywords for each action, so you now have a choice between hotkey and keyword for most actions.
-   Added list command which will output the path of all items currently in your pocket and add to your clipboard without removing the items from your pocket.

#### 1.0.0

Initial Release
