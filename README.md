## Windows 10 Dark & Light Mode Themes for XnView MP 

![Promo_1_DM](https://github.com/user-attachments/assets/40cc78d1-67b9-41b3-b5c5-63778c9a4702)

![Promo_1_LM](https://github.com/user-attachments/assets/d725fbdc-25d3-41d1-b078-022e9e8c60a3)

![Promo_2_DM](https://github.com/user-attachments/assets/66ea444f-45e7-4570-9098-25f13a3341fe)

![Promo_2_LM](https://github.com/user-attachments/assets/ce07d684-28d4-4bb0-b013-fcc85956c667)

### Installation

1. Delete all files & directories inside `UI` directory in **XnView MP** location, i.e. `C:\Program Files\XnView MP\UI`.

2. Extract `theme` directory to `%UserProfile%\AppData\Roaming\XnViewMP`.

3. If you'd like to get all the settings as shown in themes previews, you should extract files from `dm` or `lm` in `Settings` directory to `%UserProfile%\AppData\Roaming\XnViewMP` (please use installation step 4 and release note 1 if you want to keep your own settings):
      - `xnview.ini` - general settings file (with default window sizes for all dialogs)
      - `default.bar` - toolbars settings
      - `default.cmenu` - context menu settings

4. If you skipped copying `xnview.ini`, then launch **XnView MP** and apply theme using `Tools → Settings → General → Theme → 'Windows 10 Light' / 'Windows 10 Dark' → OK`, then relaunch **XnView MP**.

### Release Notes

1. In case you'd like to use your own settings, you will have set the following colors in `Settings` to make sure the file labels text are visible and readable in `Browser` view:
   - **Dark Mode**
     - `Browser` → `Preview background color` → `#202020`
     - `View` → `Background color` → `#202020`
     - `File list` → `Format colors` → enable `Use color based on file format` → `Default color 1` `#202020`, `Default color 2` `#727272`, disable `Use color based on file format`
   - **Light Mode**
     - `Browser` → `Preview background color` → `#F5F6F7`
     - `View` → `Background color` → `#F5F6F7`
     - `File list` → `Format colors` → enable `Use color based on file format` → `Default color 1` `#F5F6F7`, `Default color 2` `#000000`, disable `Use color based on file format`

2. Both themes were tested with UI scaling at 200% in Windows 10, version 21H2 and with UI scaling at 100% with Windows 7 SP1, the appearance of themes when used with other operating systems and UI scaling may be not as advertised.

3. Separators of the toolbars were made invisible because **XnView MP** lacks any other toolbar spacers that can be used to group toolbar buttons.

4. The "mouseover" design of the drop-down button of toolbar buttons and the slider indicator in dialogs will not use Windows 10 UI style, when the theme is used in Windows 7 SP1 (both elements will match Windows 7 UI style).

5. Please use [this forum thread](https://newsgroup.xnview.com/viewtopic.php?f=61&t=40313) for feedback.

### Download

**[GitHub](https://github.com/bananakid/xnviewmp-w10-qss/releases)**

### Legal Notes

This project is licensed under the terms of the [MIT License](https://opensource.org/license/mit/).
