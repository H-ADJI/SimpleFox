![image](assets/head.png)

<p style="margin: -20px 0 30px">
  <a href="https://www.buymeacoffee.com/migueravila" target="_blank" style='margin-right:0px; margin-top:5px'>
    <img align="center" src="https://github.com/migueravila/SimplerentFox/blob/dev/assets/donation.png" alt="donation" height="35px" />
  </a>
</p>

<br />

## 👇 Index

- [👇 Index](#-index)
- [💫 Features](#-features)
- [⚙️ Installation](#️-installation)
- [🚀 Usage](#-usage)
- [🎨 Customization](#-customization)
  - [💛 Colors](#-colors)
- [🍱 Startpage](#-startpage)

## 💫 Features

-   Supports Firefox **Proton UI** 
-   **As simple as you want**: All code is commented!
-   **Variables** for custom colors: [Customization](#customization)
-   **Keyboard** Centered Design! Here you can read about the shortcuts: [Usage](#usage)

## ⚙️ Installation

1. In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
3. Go to your Firefox profile:
    - If you're on Linux: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`
    - If you're on Windows: `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX` 
4. Move the `chrome` folder into the directory.
5. Make all the customizations you want [here](#-customization).
6. Enjoy!

## 🚀 Usage

This userstyle was made for a keyboard centered usage, like Tilling Window Manager users or just cool people that loves them! Use the following for a better experience:

-   `Alt` You can access to the global menu for an extended options you need
-   `Alt + Left Arrow` You can go Back
-   `Alt + Right Arrow` You can go Forward
-   `Ctrl + L` focuses the URLBar, which is very useful for quick searches and bookmarks usage
-   `Ctrl + B` shows you the Bookmarks 
-   `Ctrl + H` shows you the History Bar
-   `Ctrl + T` Opens a new Tab
-   `Ctrl + W` Closes a Tab
-   `Ctrl + Shift + T` Re-opens a tab that you just closed
-   `Ctrl + R` Refresh the page you're on
-   `Ctrl + Shift + A` Quick open for Add-Ons

## 🎨 Customization

All the configuration will be managed in the `userChrome.css` file. And also all the code is commented so you can easily change values and colors as you like.

### 💛 Colors

In this section of the code you can change the colors, there's a window color and a tabs / urlbar color. 

```css

:root {
  --sfwindow: #19171a;
  --sfsecondary: #201e21;
}

```

## 🍱 Startpage

If anyone has the doubt, in almost all of the screenshots you can see a Startpage made for it. It's called [Bento 🍱](https://github.com/MiguelRAvila/Bento) and It's another project I made. It fits with the Firefox theme because It's done with the same principles: Minimalist, Simple and Elegant.

![bento](https://github.com/migueravila/Bento/blob/master/assets/img/subheader.png)