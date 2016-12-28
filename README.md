# Machine configuration on Windows

Machine configuration for my Samsung Ativ Book 9 plus.

## `clickpad-config.reg`

This disables the "regular right click mouse" when a click is made in the bottom right area of the clickpad to make the entire clickpad left-clickable. This also enables the "regular middle click mouse" when a click is made with three fingers.

The `clickpad-config.reg` file should not be executed as it as this is a "dumb" export from `regedit` and would replace your entire current clickpad configuration located in `HKEY_CURRENT_USER\SOFTWARE\Elantech\SmartPad`. The only interesting part is the following:

- `ClickPad_RightCorner_Click_Enable`
- `ClickPad_Three_Finger_Click_Enable`
