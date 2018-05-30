Material Safari style for Firefox
---

This style was originally designed and made by @Mr-Seek on reddit (<https://www.reddit.com/r/FirefoxCSS/comments/8h81bv/material_safari_windows_10/>), all credits go to the original author.

![screenshot 1](screenshots/theme.gif)

What I did was:

- Fixed layout on Firefox for Linux
- Refined some details of the theme

Installation
---

Before installation, please ensure that `Client Side Decoration (CSD)` is enabled, theme is set to `Light`, and density is set to `Compact`

On Linux, locate your profile directory in `~/.mozilla/firefox/`. The profile directory often starts with a random string and ends with something like `.default`. You can also fetch the path from the `about:support` page.

Once located, navigate into the directory, and run

```bash
git clone https://github.com/PeterCxy/firefox-material-safari.git chrome
```

Then restart Firefox.
