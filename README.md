# TeXstudio-QSS-Stylesheet
Dark mode QSS stylesheet (WIP). Built around a dark colour scheme (majority being different shades of gray and dark blue), with red and blue accents. Also red text highlighting, instead of the default Windows blue. `:)`

Slightly modified from (and credits to):
- https://github.com/ColinDuquesnoy/QDarkStyleSheet/tree/master/qdarkstyle

## Sample images:

![](https://github.com/thatlittleboy/TeXstudio-QSS-Stylesheet/blob/master/sample%20imgs/editor%20and%20pdf%20viewer.png)

![](https://github.com/thatlittleboy/TeXstudio-QSS-Stylesheet/blob/master/sample%20imgs/config%20menu.png)

### Disclaimer
Stylesheet does not set (i) the background colour and syntax highlighting of the editor window (mine is modified from Solarized Dark theme), (ii) the internal PDF viewer background colour and (iii) the internal PDF viewer highlight colour. For that, set it from within the TXS settings (or modify `texstudio.ini`).

## To Do / Unsure how to fix at the moment:
- Symbols side panel and a few icons are black (on transparent background?), thus are hard to see with the dark background of everything else (c.f. `Math -> Math Accents`). Whereas others (c.f. `LaTeX -> Font Styles`) are fine;
- Table in `Config TeXstudio -> Syntax Highlighting` is a mess.. Not sure how much of it can be influenced/fixed by QSS;
- Some pop-up dialogs still not inheriting the QSS, (c.f. `Edit Macros` dialog, `Select Color` dialog);
- The "right-click context menu" not inheriting QSS as well;
