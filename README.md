# SpecialCharacters.ahk
This is the <a href="https://www.autohotkey.com/">AutoHotkey</a> script I use to type common special characters, including Spanish accented letters, superscripts, math and science symbols. I've also included shortcuts to simulate the media control keys.

You can copy and paste the script, or <a href="https://bradshacks.com/Bin/SpecialCharacters.exe">download a precompiled version</a> that doesn't require AutoHotkey to run.

You can put it in <strong>%appdata%\Microsoft\Windows\Start Menu\Programs\Startup</strong> (navigate to this quickly by running "shell:startup" in the Run box) to have it automatically run at Windows startup.

This is written in AutoHotkey 2.0 syntax.
'!' means Alt, '+' means Shift, '^' means Control, so '!a' means pressing 'Alt' and 'A' together.

## Editing & Compiling
You can edit this AHK file using any text/code editor, such as Visual Studio Code with the "AutoHotkey v2 Language Support" extension.

Then, you can compile it into an exe file using [Ahk2Exe](https://github.com/AutoHotkey/Ahk2Exe). Select "C:\Program Files\AutoHotkey\v2\AutoHotkey64.exe" as the Base File, since this script is in AHK v2 syntax.

I've included the ICO icon file in the repo. You can specify the icon in Ahk2Exe.
