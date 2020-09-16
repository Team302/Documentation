# Intellisense in VS Code:    
---

This is from this [Chief Delphi topic](https://www.chiefdelphi.com/t/intelli-non-sense-help/375155/3)

1. It’s actually not a Gradle issue, it’s just that occasionally the vscode engine gets confused. Follow the following steps to try and reset everything.
2. Make sure you’re not getting any popups saying you’re in the wrong folder when opening vscode, or any other popups.
3. Make sure you didn’t accidentally create a c_cpp_properties.json file in the .vscode folder. It breaks everything. If it’s there, delete it.
4. Close all files in vscode. Leave vscode open.
5. Run the refresh c++ intellisense command in vscode.
6. Once that finishes, in the bottom right you should see something that looks like a platform (linuxathena or windowsx86-64 etc). If it’s not linuxathena click it and set it to one of the linuxathena one.
7. Wait one minute (yes one whole minute don’t skip this)
8. Open your main cpp file (not a header file). Intellisense should now be working.
9. Not closing vscode while doing this is key, closing it will reset the process. You just have to close all the tabs.