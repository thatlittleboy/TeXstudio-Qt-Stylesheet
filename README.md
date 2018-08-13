# TeXstudio-Qt-Stylesheet
Dark mode Qt stylesheet (WIP), developed primarily for TeXstudio, a LaTeX editor. Built around a dark colour scheme (majority being different shades of gray and dark blue), with red and blue accents. Also, there's red text highlighting, instead of the default Windows blue, for fun! `:)`

Slightly modified from (and credits to):
- https://github.com/ColinDuquesnoy/QDarkStyleSheet/tree/master/qdarkstyle

## To Use:
**Mandatory:**
Place `stylesheet.qss` and the `rc` folder into [TXS config folder](https://github.com/texstudio-org/texstudio/wiki/Frequently-Asked-Questions#where-are-the-settings-stored).

For **best effects** (cf. sample images): I would recommend using the following settings (change under `Options -> Configure TeXstudio`):
- `General -> Color Scheme -> Modern` (instead of Classic);
- `Syntax Highlighting`: Choose a dark colour scheme you like from [How can I set a dark theme in TeXstudio?](https://tex.stackexchange.com/q/108315)

**Optionally/Personal taste:** Change the internal PDF viewer background colour, and the internal PDF viewer highlight colour. You can customize this in `Options -> Configure TeXstudio -> Internal PDF viewer -> Paper Color` and `Highlight Color`. You'll need `Show Advanced Options` checked in the bottom left hand corner of the config dialog to see these options.

## Sample images:

![](https://github.com/thatlittleboy/TeXstudio-QSS-Stylesheet/blob/master/sample%20imgs/editor%20and%20pdf%20viewer.png)

![](https://github.com/thatlittleboy/TeXstudio-QSS-Stylesheet/blob/master/sample%20imgs/config%20menu.png)

<!--
<table style="width:100%">
  <tr>
    <th colspan=2>Containers (no tabs) and Buttons</th>
  </tr>
  <tr>
    <td><img src="./screenshots/qdarkstyle_containers_buttons.png"/></td>
    <td><img src="./screenshots/no_dark_containers_buttons.png"/></td>
  </tr>
  <tr>
    <th colspan=2>Containers (tabs) and Displays</th>
  </tr>
  <tr>
    <td><img src="./screenshots/qdarkstyle_containers_tabs_displays.png"/></td>
    <td><img src="./screenshots/no_dark_containers_tabs_displays.png"/></td>
  </tr>
  <tr>
    <th colspan=2>Widgets and Inputs (with fields)</th>
  </tr>
  <tr>
    <td><img src="./screenshots/qdarkstyle_widgets_inputs_fields.png"/></td>
    <td><img src="./screenshots/no_dark_widgets_inputs_fields.png"/></td>
  </tr>
  <tr>
    <th colspan=2>Views and Inputs (without fields)</th>
  </tr>
  <tr>
    <td><img src="./screenshots/qdarkstyle_views_inputs_no_fields.png"/></td>
    <td><img src="./screenshots/no_dark_views_inputs_no_fields.png"/></td>
  </tr>
</table>
-->

### Disclaimer
Stylesheet does not set (i) the background colour and syntax highlighting of the editor window (mine is modified from Solarized Dark theme), (ii) the internal PDF viewer background colour and (iii) the internal PDF viewer highlight colour. For that, set it from within the TXS settings (or modify `texstudio.ini`), described above.

## To Do / Unsure how to fix at the moment:
- Symbols side panel and a few icons are black (on transparent background?), thus are hard to see with the dark background of everything else (c.f. `Math -> Math Accents`). Whereas others (c.f. `LaTeX -> Font Styles`) are fine;
- <s>Table in `Config TeXstudio -> Syntax Highlighting` is a mess.. Not sure how much of it can be influenced/fixed by QSS;</s> Fixed since [git_0ba02d0](https://github.com/texstudio-org/texstudio/commit/0ba02d0250a6ffb1a9302966ff8820194e17d336).
- Some pop-up dialogs still not inheriting the QSS, (c.f. `Edit Macros` dialog, `Select Color` dialog);
- The "right-click context menu" not inheriting QSS as well;
