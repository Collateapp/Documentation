---
title: How to export from Evernote to Collate
tags: []
type: markdown
modified: '2017-05-12T01:41:30.242Z'
---
See the full documentation online [with screenshots]([https://collatenotes.com/export-from-evernote/)

To export your data from Evernote, you’ll need to have the desktop Evernote application installed and your data synced.

This process will require you to export your note data into a single .enex file, your attachments into a separate directory, and then import them via Collate’s import tool. Please note that import may fail due to unforeseen factors and artifacts in the .enex files. We do the best we can but it’s quite difficult to parse and convert sometimes. Just let us know if you run into any issues.

**Evernote features that can not be ported:**

* Encrypted notes
	* Encrypted notes will be shown as encrypted text in Collate
* Checkboxes
	* Checkboxes do not appear.
* Inline attachments
	* Evernote attachments that are shown in-line will be removed and placed in each note’s attachment folder.  This includes inline images.
* Tables
	* Tables are stripped and lose formatting.
* HTML
	* HTML tags are stripped out of Evernote files while cleaning up Evernote ENML markdown.

**Step 1: Export your note data**

Open Evernote.  On the left hand side pane, click Notes to view all your notes.  Click on a note, and select all (Cmd + a on Mac or Ctrl + a on Linux/Windows).

In the menubar, click File, and choose Export Notes…

Name your export and choose a place to save it.  In this example, I called my export file EvernoteExport and I will be saving it to my desktop.  Make sure that Include tags for each note is checked.

Click save.  You should now have a file ending in .enex.

**Step 2: Export your attachments**

Click File in the toolbar again, and this time choose Save Attachments to Folder.

You’ll need to create a new folder to save your attachments in.  For ease, create it in the same location as your .enex file.  In this example, I’m creating this folder on my desktop.

Select the new folder and click save. Evernote will save any files you’ve attached to your notes into this folder.

**Step 3: Import into Collate**

Open Collate.

In the menubar, choose Collate -> Import

Select the .enex file and attachments folder, name your new notebook and click import.

**Conclusion**

Your notes should now show up in your notebook list.

**Preserve your Evernote Notebook structure**

If you’d like to preserve your Evernote Notebook structure, you will need to export all the notes from each notebook into separate .enex files.

Complete the steps above except in Step 1 where instead of selecting all notes under Notes, you will choose a notebook, click File -> Export Notes from “Notebook Name”


Do this for each notebook you would like to export.

Export attachments as per the instructions in Step 2.

When importing into Collate, import each .enex file into different notebook names.  Use the same attachment folder for all imports.
