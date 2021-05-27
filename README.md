# EasyHtmlEditor
This is a fork of [HtmlEditorWPF](https://github.com/LBRNZ/HtmlEditorWPF) wich is a fork of [SmithHtmlEditor](https://github.com/adambarath/SmithHtmlEditor).

## Improvements
- migrated to .NET 4.5

## Preview
![](Readme/preview.PNG?raw=true)

# Discontinued !
After testing the current functionality, I decided not to use this component and write my own.
- During the testing it crashed a few times (exceptions coming from commands, other exceptions comming from WinFormsIntegration)
- New ENTER functionality doesn't work as expected (is inserting 2 new lines)
- After changing font style (Bold, Italic, ...) and moving the cursor back to editor it selects all the text
- *maybe some other problems. At this point I stopped testing and started working on custom Editor from scratch*
