# CustomWindow11UI (Saint Cecilia theme from the series Saint Cecilia and Pastor Lawrence)

CustomWindow11UI is a demonstration project that showcases how to personalize the Windows 11 user interface with a polished, themed experience.

## Overview

This project combines multiple tools to customize the Windows 11 interface, including the Start menu, wallpaper, taskbar, bootscreen, notification center, context menu, and other UI elements.

## Theme

The UI customization is built around the "Saint Cecilia" theme, inspired by the Saint Cecilia and Pastor Lawrence series.
<img width="1920" height="1080" src="https://github.com/user-attachments/assets/9362c1f4-2da7-46c1-b4f9-00e90db01be7" />


## Included Tools

- **Windhawk**
- **Nilesoft Shell**
- **Wallpaper Engine**
- **HackBGRT**

## Important

In the Taskbarsyler.json and Startmenu.json there are custompath to images for the 
Taskbar Styler:
- Startmenu icon (Normal, Hover, Active Normal, Active Hover)
``` Json
    "controlStyles[41].styles[0]": "Background@InactiveNormal:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C://Users//nam45//Documents//icon.png\" />",
    "controlStyles[41].styles[1]": "Background@InactivePointerOver:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C://Users//nam45//Documents//iconhover.png\" />",
    "controlStyles[41].styles[2]": "Background@InactivePressed:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C://Users//nam45//Documents//icon.png\" />",
    "controlStyles[41].styles[3]": "BorderThickness=0",
    "controlStyles[41].styles[4]": "Background@ActiveNormal:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C://Users//nam45//Documents//icon1.png\" />",
    "controlStyles[41].styles[5]": "Background@ActivePointerOver:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C://Users//nam45//Documents//iconhover.png\" />",
    "controlStyles[41].styles[6]": "Background@ActivePressed:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C://Users//nam45//Documents//icon2.png\" />"
```
Startmenu Styler:
- Startmenu overlay
``` Json
"controlStyles[0].styles[4]": "Background:=<ImageBrush ImageSource=\"C:\\Users\\nam45\\Documents\\startmenubg.png\" Stretch=\"UniformToFill\" />"
```
Be sure to replace it with your own path!
## Purpose

The goal of this project is to demonstrate how Windows 11 can be adapted and styled using third-party utilities and custom themes. It is intended as a reference for creating a unified, customized desktop experience.
