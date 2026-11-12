# Puma 0.6.72

An independent Puma infantry fighting vehicle MOD for Gunner, HEAT, PC!

## Download and install

Get **Puma-0.6.72-Full.zip** from https://github.com/AIM928/Puma/releases/latest .
This is the complete runtime package. Do not download GitHub's automatically generated Source code archive to install the MOD.

1. Install GHPC and MelonLoader. This package was built against the locally installed GHPC build and MelonLoader 0.7.3.
2. Close GHPC, then extract the ZIP into the game's **Bin** directory. Merge its **Mods** folder with the existing one. Keep both **PumaVJTF.dll** and **PumaVJTFAssets** together; these internal filenames are retained for upgrade compatibility.
3. Start the game and enter the main menu. On a new installation, the Chinese-left / English-right quick-start panel appears automatically. Select **Got it** to dismiss it permanently for that installation.
4. Select **Puma** in the mission customizer. Restart GHPC after updating the MOD.

## Quick controls

- Middle mouse: lock a target; press again to unlock. Backspace: clear lock.
- Hold right mouse to fine-adjust while locked.
- Q menu: autocannon rate, laser rangefinder and Spike TV mode.
- Thermal imaging, magnification and view switching use the game's configured bindings.

## Included

- 30 mm autocannon, DM33 / DM21 ammunition and selectable firing rates.
- Spike missiles, target tracking and TV mode.
- Independently rotating infrared countermeasures and laser warning display.
- ERA protection with spent-module appearance and X-ray displays.
- Updated AI search and missile use, a two-second minimum missile launch interval, and same-target in-flight reservation.
- Commander exterior view adjustment, original track finish and recent display/update optimizations.

The introduction recommends the **LATEST VERSION of our M1 Trophy MOD** and links to its permanent project homepage: https://github.com/AIM928/M1-Trophy . M1 Trophy is optional, not a dependency.

## First-run panel

The download does not contain any UserData, acknowledgement marker, personal settings, logs or caches. A first-time user will therefore have no saved acknowledgement and will see the panel when the main menu is ready and the game has focus.
After Got it is clicked, the acknowledgement is saved under **Bin/UserData/PumaVJTF/welcome-v1.seen**. Existing users who already acknowledged it will not see it again. The MOD does not reset this choice on every update.

首次安装进入主菜单会显示左中文、右英文的介绍页；点击“开始使用”后不再自动弹出。升级不会清除已有的确认记录。

## Validation

The release package is checked for required runtime assets, first-run acknowledgement behavior, bilingual layout, camera offset, warning updates and existing native-game regressions in an isolated Unity environment. These checks are not a measurement of in-game FPS; mission-specific compatibility and frame-time gains still depend on the game and other installed MODs.

Unofficial community MOD; not affiliated with the game developers. No base-game executable, MelonLoader distribution, unrelated MOD or personal data is included.

## Credits

Retopologized War Thunder vehicle model and original textures: **Gaijin Entertainment**.
GHPC integration and tuning: AIM. Unofficial fan mod; original assets remain the property of their respective owners.
