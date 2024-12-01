## Windows 10 Dark & Light Mode Themes for XnView MP

![promo_1_dm.png](https://github.com/user-attachments/assets/c5b42419-2ceb-4da4-b176-0e122e264ce5)

![promo_1_lm.png](https://github.com/user-attachments/assets/c2699f3a-b8d2-4eff-a1bb-774285e66e7a)

![promo_2_dm.png](https://github.com/user-attachments/assets/c0c8cf8c-0389-4d8e-8ba7-33796a593498)

![promo_2_lm.png](https://github.com/user-attachments/assets/2c857c0c-d037-4225-aeb0-46ec74830801)

### Installation

1. Delete all files & directories inside `UI` directory in **XnView MP** location, i.e. `C:\Program Files\XnView MP\UI`.

2. Copy directory `ui\svg` to corresponding directory in **XnView MP** location, i.e. to `C:\Program Files\XnView MP\UI`.

3. **XnView MP** doesn't provide a working UI to switch theme, so you have to do it manually:
   - **Dark Mode**
      - copy `dm\style_sheet.qss` to `%UserProfile%\AppData\Roaming\XnViewMP`
   - **Light Mode**
      - copy `lm\style_sheet.qss` to `%UserProfile%\AppData\Roaming\XnViewMP`

4. If you'd like to get all the settings as shown in themes previews, you should copy corresponding files from `dm` or `lm` directory to `%UserProfile%\AppData\Roaming\XnViewMP` (please see first release note below if you want to keep your own settings):
   - `xnview.ini` - general settings file (with default sizes for XnView MP's windows)
   - `default.bar` - toolbars settings
   - `default.cmenu` - context menu settings

5. If you skipped copying `xnview.ini`, then launch **XnView MP** and apply theme using `View → Theme → Old dark → Apply` and relaunch **XnView MP**.

### Release Notes

1. In case you`d like to use your own settings, you will have set the following colors in `Settings` to make sure the file labels text are visible and readable in `Browser` view:
   - **Dark Mode**
     - `Browser` → `Preview background color` → `#202020`
     - `View` → `Background color` → `#202020`
     - `File list` → `Format colors` → enable `Use color based on file format` → `Default color 1` `#202020`, `Default color 2` `#727272`, disable `Use color based on file format`
   - **Light Mode**
     - `Browser` → `Preview background color` → `#F5F6F7`
     - `View` → `Background color` → `#F5F6F7`
     - `File list` → `Format colors` → enable `Use color based on file format` → `Default color 1` `#F5F6F7`, `Default color 2` `#000000`, disable `Use color based on file format`

2. Both themes were tested with UI scaling at 200% in Windows 10, version 21H2 and with UI scaling at 100% with Windows 7 SP1, the appearence of themes when used with other operating systems and UI scaling may be not as advertised.

3. Separators of the toolbars were made invisible because **XnView MP** lacks any other toolbar spacers that can be used to group toolbat buttons nicely by blank spaces of different size.

4. The file format colors aren't previewed in `Settings → File list → Format colors`.

5. Slight 'jump' of `Quick filter` may occur when this UI element is accessed by **XnView MP** for the first time during current session (i.e. when launching **XnView MP** in `Browser` view  with `Filelist toolbar` enabled in `View` menu).

6. The "mouseover" design of the drop-down button of toolbar buttons and the slider indicator in dialogs will not use Windows 10 UI style, when the theme is used in Windows 7 SP1 (both elements will match Windows 7 UI style).

7. Please use [this forum thread](https://newsgroup.xnview.com/viewtopic.php?f=61&t=40313) for feedback.

### Download

**[GitHub](https://github.com/bananakid/xnviewmp-w10-qss/releases)**

### Legal Notes

This project is licensed under the terms of the [MIT License](https://opensource.org/license/mit/).
