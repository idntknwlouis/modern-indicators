### ![replugged](https://discord-extensions.github.io/assets/icons/replugged.png) **[Replugged](https://replugged.dev)**
- [Direct Install](https://youtu.be/dQw4w9WgXcQ)

### ![betterdiscord](https://discord-extensions.github.io/assets/icons/betterdiscord.png) **[BetterDiscord](https://betterdiscord.app)**
- [Direct Download](https://github.com/idntknwlouis/modern-indicators/releases/download/update/modern-indicators.theme.css)
- [Compiled Source](https://idntknwlouis.github.io/modern-indicators/src/source.css)

### ![vencord](https://discord-extensions.github.io/assets/icons/vencord.gif) **[Vencord](https://github.com/Vendicated/Vencord)**
- [Direct Download](https://github.com/idntknwlouis/modern-indicators/releases/download/update/modern-indicators.theme.css)

    **Or**

1. Go to user settings (CTRL + ,)
2. Go to the "Vencord" category and select the "Themes" tab.
3. In the input field under "THEMES" paste the following URL.
```css
https://idntknwlouis.github.io/modern-indicators/modern-indicators.css
```
or QuickCSS
```css
@import url("https://raw.githubusercontent.com/idntknwlouis/modern-indicators/refs/heads/main/src/source.css");
```

### ![stylus](https://discord-extensions.github.io/assets/icons/stylus.png) **Stylus**
> **Warning**
> Firefox users must have "Patch CSP to allow style assets" enabled for the theme to work. This can be found in Stylus' settings under "Advanced"
1. Install the browser extensions for your respective browser.
    - [Chrome Webstore](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
    - [Firefox Addons](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
2. Once installed, open [this link](https://github.com/idntknwlouis/modern-indicators/blob/main/clients/modern-indicators.user.css) in a new browser tab. This opens the page where you will install this userstyle.
3. Press the `Install Style` button.
---
### Customization
You can add the variables below into your Quick CSS and modify the basic colors. Please use HSL values.
```css
/* Modern Indicators CSS Config */
:root {
  /* Important Channel */
  --indicator-border-size: 2px;
  --indicator-border-style: solid;
  --indicator-rounding: 0;

  /* Less Important Channel */
  --less-indicator-border-size: 2px;
  --less-indicator-border-style: solid;
  --less-indicator-rounding: 0;
}

.theme-light {
  --indicator-unread: var(--primary-900-hsl);
  --indicator-unread-mention: var(--red-430-hsl);
  --indicator-selected: var(--brand-500-hsl);
  --indicator-connected: var(--green-430-hsl);
}

.theme-dark {
  --indicator-unread: var(--primary-130-hsl);
  --indicator-unread-mention: var(--red-400-hsl);
  --indicator-selected: var(--brand-500-hsl);
  --indicator-connected: var(--green-230-hsl);
}
```
---
### Licensing
This theme is licensed under the MIT license. Please refer to the [LICENSE](./LICENSE) file for more details regarding rights and limitations.

### Credits
Everyone who has contributed can be found on the [CREDITS.md](./CREDITS.md) file.

## I have no server yet (as of Nov.27, 2024). so you can just report an issue here for now.
~~Support Server
If you are having any issues with the theme, feel free to join the [support server]('I have no server yet. so you can just report an issue here for now'), or make an issue on this repository.~~
