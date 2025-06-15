# macos-new-text-file
Quickly create a new text file in the current Finder window (Cmd+Space n).


https://github.com/user-attachments/assets/95b78dec-013c-4d9e-9639-e793aec85a91



If you're coming from Windows, you might notice macOS Finder is missing that handy "New Text File" feature.

Instead, you have to break your workflow, open TextEdit, navigate to the right folder, and create a new file.

Some apps let you create a text file from the context menu, but they either need accessibility permissions, only work on right-clicked subfolders, or you just don’t trust 3rd-party apps.

This AppleScript is just a few lines of code that lets you create a new text file in the current Finder window with (Cmd+Space n).

You can trust yourself to edit, run, and export the script right on your own Mac.

## Edit & Export to .app
- Open **Script Editor** (installed with your macOS), go to File → New, and paste the content of `New Text Document`.
- (Optional) Modify `baseName` and `extension` if needed (in the config section at the beginning of the script).
- Go to File → Export, choose **Application** as the file format, and save the new `New Text Document.app` to **Applications**.

## Uses
Now that you have `New Text Document.app` in Applications, you can run it from Spotlight by pressing Cmd+Space, then `n`.
