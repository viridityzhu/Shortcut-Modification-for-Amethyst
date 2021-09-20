# Shortcut-Modification-for-Amethyst
My modification for shortcuts of Amethyst, a window layout manager on MacOS. Suitable for 2 monitors.

Today I installed a window layout manager on MacOS -- [Amethyst](https://github.com/ianyh/Amethyst). It allows to use shortcuts to swich windows into different layouts. Because I am using 2 monitors, and always work with lots of windows together, I really need one to smoothly set up the layouts. 

In fact, I wanted an app to help me remember the layouts and automatically recover it at the beginning. And I've downloaded the **Layouts**. But I don't wanna learn to use 2 apps together. I hope I'll make use both of them one day.

### Shortcuts for me

Here I comment on the default shortcuts. I myself has only 2 monitors, so I don't need some of the functions.

Amethyst uses two modifier combinations.

| Default Shortcut | Description             |
| ---------------- | ----------------------- |
| `mod1`           | `option + shift`        |
| `mod2`           | `ctrl + option + shift` |

| Default Shortcut | Description                                                  |
| ---------------- | ------------------------------------------------------------ |
| `mod1 + space`   | ~~Cycle layout forward~~                                     |
| `mod2 + space`   | ~~Cycle layout backwards~~                                   |
| `mod1 + h`       | **main pane缩小。**Shrink the main pane                      |
| `mod1 + l`       | **main pane扩大。**Expand the main pane                      |
| `mod1 + ,`       | **main pane 增加数量** Increase main pane count              |
| `mod1 + .`       | **main pane减少数量** Decrease main pane count               |
| `mod1 + j`       | **逆时针移动焦点。**Move focus counter clockwise             |
| `mod1 + k`       | **顺时针移动焦点。**Move focus clockwise                     |
| `mod1 + p`       | ~~Move focus to counter clockwise screen~~                   |
| `mod1 + n`       | ~~Move focus to clockwise screen~~ no need coz I've only 2 screens |
| `mod2 + h`       | ~~Swap focused window to counter clockwise screen~~          |
| `mod2 + l`       | ~~Swap focused window to clockwise screen~~                  |
| `mod2 + j`       | **逆时针移动当前pane** Swap focused window counter clockwise |
| `mod2 + k`       | **顺时针移动当前pane** Swap focused window clockwise         |
| `mod1 + enter`   | **把当前pane作为main pane** Swap focused window with main window |
| `mod1 + z`       | ？Force windows to be reevalulated                           |
| `mod2 + z`       | Relaunch Amethyst                                            |
| `mod2 + left`    | **把当前pane移到左边的桌面** Throw focused window to space left |
| `mod2 + right`   | **把当前pane移到右边的桌面** Throw focused window to space right |
| `mod2 + 1`       | **把当前pane移到桌面1** Throw focused window to space 1      |
| `mod2 + 2`       | **移到桌面2** Throw focused window to space 2                |
| `mod2 + 9`       | **移到桌面9** Throw focused window to space 9                |
| `mod2 + 0`       | **移到桌面10** Throw focused window to space 10              |
| `mod1 + w`       | **聚焦显示屏1** Focus Screen 1                               |
| `mod2 + w`       | **移动pane到显示屏1** Throw focused window to screen 1       |
| `mod1 + e`       | **聚焦显示屏2** Focus Screen 2                               |
| `mod2 + e`       | **移动pane到显示屏2** Throw focused window to screen 2       |
| `mod1 + r`       | ~~Focus Screen 3~~                                           |
| `mod2 + r`       | ~~Throw focused window to screen 3~~                         |
| ~~`mod1 + q`~~   | ~~Focus Screen 4~~                                           |
| `mod2 + q`       | ~~Throw focused window to screen 4~~                         |
| ~~`mod1 + t`~~ q | **float，暂时不要amethyst** Toggle float for focused window  |
| `mod1 + i`       | **显示当前布局** Display current layout                      |
| `mod2 + t`       | ？Toggle global tiling                                       |
| ~~`mod1 + a`~~ t | **tall layout** Select tall layout                           |
| `none`           | Select tall-right layout                                     |
| `mod1 + s`       | ~~Select wide layout~~ I don't need wide layout, ugly        |
| `none`           | Select middle-wide layout                                    |
| ~~`mod1 + d`~~ f | **full screen** Select fullscreen layout (rotate between each of the windows) |
| ~~`mod1 + f`~~ | ~~Select column layout~~                   |
| `none`           | Select row layout                                            |
| `none`           | Select floating layout                                       |
| `none`           | Select widescreen-tall layout                                |
| `none`           | Select bsp layout                                            |
| Add: `mod1 + c` | **3Column Right** |

### A more readable version of My Shortcuts

| Modifier Combinations | Description             |
| --------------------- | ----------------------- |
| `mod1`                | `option + shift`        |
| `mod2`                | `ctrl + option + shift` |

| Move Focus | Description                             |
| ---------- | --------------------------------------- |
| `mod1 + j` | **逆时针** Move focus counter clockwise |
| `mod1 + k` | **顺时针** Move focus clockwise         |
| `mod1 + w` | **到显示屏1** Focus Screen 1            |
| `mod1 + e` | **到显示屏2** Focus Screen 2            |

| Main Pane  | Description                                     |
| ---------- | ----------------------------------------------- |
| `mod1 + h` | **main pane缩小。**Shrink the main pane         |
| `mod1 + l` | **main pane扩大。**Expand the main pane         |
| `mod1 + ,` | **main pane 增加数量** Increase main pane count |
| `mod1 + .` | **main pane减少数量** Decrease main pane count  |

| 移动pane Move Focused Pane | Description                              |
| -------------------------- | ------------------------------------------------------ |
| `mod2 + j`                 | **逆时针** Swap focused window counter clockwise       |
| `mod2 + k`                 | **顺时针** Swap focused window clockwise               |
| `mod1 + enter`             | **作为main pane** Swap focused window with main window |
| `mod2 + left`              | **到左边的桌面** Throw focused window to space left    |
| `mod2 + right`             | **到右边的桌面** Throw focused window to space right   |
| `mod2 + 1~0`               | **到桌面1~10** Throw focused window to space 1-10      |
| `mod2 + w`                 | **到显示屏1** Throw focused window to screen 1         |
| `mod2 + e`                 | **到显示屏2** Throw focused window to screen 2         |

| Layout     | Description                                              |
| ---------- | -------------------------------------------------------- |
| `mod1 + i` | **显示当前布局** Display current layout                    |
| `mod1 + q` | **float，暂时不要amethyst** Toggle float for focused window|
| `mod1 + f` | **full screen** Select fullscreen layout (rotate between each of the windows) |
| `mod1 + t` | **tall layout** Select tall layout                       |
| `mod1 + c` | **3Column Right**                                        |

| Other      | Description       |
| ---------- | ----------------- |
| `mod2 + z` | Relaunch Amethyst |


