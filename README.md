# Obsidian Portable

These are **UNOFFICIAL** portable builds of Obsidian for Windows.

**NOTE:** This will not allow you to run multiple versions of Obsidian alongside each other on the same machine. All Obsidian instances, whether installed or portable will share the same `%AppData%` folder, and can therefore conflict with each other. This is designed for use by people who cannot or do not want to install the normal Obsidian on their machine.

Download the latest build: [Obsidian Portable 1.1.9](https://github.com/alangrainger/obsidian-portable/releases/download/1.1.9/Obsidian.Portable.1.1.9.exe)

You can find all builds here: [All builds](https://github.com/alangrainger/obsidian-portable/releases)

---

## Instructions to do it yourself

If you don't want to trust an internet stranger, you can create your own portable build of Obsidian in about 5 minutes.

You must already have Obsidian installed to create a portable version of it.

1. Download Enigma Virtual Box from [https://enigmaprotector.com/en/downloads.html](https://enigmaprotector.com/en/downloads.html) and install it.

2. Run the app and it will look like this:

![](https://i.imgur.com/VZUvOXu.png)

3. Right click on your Obsidian app, right click on the word "Obsidian", then click on Properties:

![](https://i.imgur.com/ipcIGNx.png)

4. Copy the path to `Obsidian.exe`:

![](https://i.imgur.com/b84BJU5.png)

Paste that into the **Enter Input File Name** field:

![](https://i.imgur.com/JnDq0fj.png)

5. Add any path you like for output file name.

6. Click on Add, then Add Folder Recursive:

![](https://i.imgur.com/4rAJeWo.png)

7. Paste in the same folder from the `Obsidian.exe` step, click OK and choose `%DEFAULT FOLDER%`:

![](https://i.imgur.com/vJ6Mazz.png)

8. Click **Process**, and it will create the portable app for you.

![](https://i.imgur.com/oEqMMBQ.png)
