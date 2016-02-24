# Bluegrammer

Bluegrammer is a modified version of [Brogrammer](https://github.com/kenwheeler/brogrammer-theme).
I just blue the brogrammer and cleaned it up a bit

I also included a modified Monokai color scheme, which I prefer more than Brogrammer's color scheme

Preview:
![bluegrammer-preview](https://cloud.githubusercontent.com/assets/7158828/13277070/a63552f4-da7a-11e5-838f-954c8d0b38aa.png)

## Install

### Via Package Control

NOT IMPLEMENTED
~~Theme is listed as `Theme - Bluegrammer` in Will Bond's [Sublime Package Control](https://sublime.wbond.net).~~

### Manual

1. [Download the .zip](https://github.com/thomasgerstenberg/bluegrammer-theme/archive/master.zip)
2. Unzip and rename the folder to `Theme - Bluegrammer`
3. Copy the folder into `Packages` directory, which you can find using the menu item `Preferences -> Browse Packages...` in Sublime Text

or

1. Clone the repo into the `Packages` directory: `git clone git@github.com:ThomasGerstenberg/bluegrammer-theme.git "Theme - Bluegrammer"`
2. Verify that the folder name for the repo is `Theme - Bluegrammer`.  The theme will not work otherwise

## Setup

Activate the UI theme and color scheme by modifying your user preferences file, which you can find using the menu item `Preferences -> Settings - User` in Sublime Text or by clicking `cmd + ,` on a Mac.

### Example settings
```
{
  "theme": "Bluegrammer.sublime-theme",
  "color_scheme": "Packages/Theme - Bluegrammer/bluegrammer.tmTheme"
  or
  "color_scheme": "Packages/Theme - Bluegrammer/Monokai.tmTheme"
}
```
