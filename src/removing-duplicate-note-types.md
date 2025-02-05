# Removing duplicate note types

After you have used Anki for a while, you may find you have multiple note types with the same name followed by different characters, like `Basic-908e4`, `Cloze-37a28`, or `Image Occlusion++++`. This can happen when you import a shared deck that uses a note type with the same name as one that is already in your collection, or if you create a note type with a duplicate name. Anki adds characters to the name to avoid merging or overwriting the existing note type.

While these "duplicate" note types are generally harmless, it can be somewhat confusing if you can't tell which note type you are using. To clean that up, you can do the following:

1. Compare the fields, card templates, and styling of each of the note types by clicking <kbd>Fields</kbd> and <kbd>Cards</kbd> in the Manage Note Types window (Notes → Manage Note Types).
   * If they are the same, decide which note type to delete and click <kbd>Rename</kbd> to change its name so you will know which one it is (e.g., add `-delete` to the name).
   * If they aren't the same, rename one to something more descriptive, and keep them both. 
2. In the Browse window, in the left Sidebar, select the note type that you want to delete, then choose Edit → Select All to select all of its notes/cards.
3. Choose Notes → Change Note Type and select the note type that you are keeping from the dropdown on the right side of the screen. \[This step will require a one-way sync the next time you sync with AnkiWeb, so if you have unsynced progress on other devices, you should stop here and get your devices in sync. Anki will give you a warning about this.\] Verify that the fields and templates are mapping as you expect. Click Save. 
4. Repeat steps 2 & 3 for any other note types you want to delete. 
5. Open the Manage Note Types window again and delete the now-unused note types (each will say it is used by "\[0 notes\]"). 
