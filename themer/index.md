# Themer plugin guide

## How to create my own theme
- [Documentation](https://github.com/Aliucord/documentation/blob/main/theme-dev)
- [Theme maker](https://aliucord.com/theme-maker)

## How to set a custom background
- Install [Themer](https://github.com/Vendicated/AliucordPlugins/raw/builds/Themer.zip) plugin ([manual way](https://yutaplug.github.io/Aliucord/beginner/#how-to-install-a-plugin-manually-required-for-unmaintained-plugins-channel))
- Install [this file manager](https://play.google.com/store/apps/details?id=me.zhanghai.android.files) & open it (or any file manager that lets you copy file paths)
- Find the image/gif file
- Click the 3 dots next to it & press `Copy path`
- Go to Themer settings → your theme → `Background` & paste it
- Add `file:/` at the start
 
Final result should be `file://storage/emulated/0/Example/Example.jpg`
 
Don't forget to enable transparency (chat, chat & settings). If you want full transparency, you need to use the template

## How to set a custom font
- Install [Themer](https://github.com/Vendicated/AliucordPlugins/raw/builds/Themer.zip) plugin ([manual way](https://yutaplug.github.io/Aliucord/beginner/#how-to-install-a-plugin-manually-required-for-unmaintained-plugins-channel))
- Install [this file manager](https://play.google.com/store/apps/details?id=me.zhanghai.android.files) & open it (or any file manager that lets you copy file paths)
- Find the font file
- Click the 3 dots next to it & press `Copy path`
- Go to Themer settings → your theme → `Fonts` & paste it where the asterisk is
- Add `file:/` at the start
 
Final result should be `file://storage/emulated/0/Example/Example.ttf`
 
Don't forget to enable the `Enable Custom Fonts` option in Themer settings

## Why does my background image not work
- You didn't enable transparency
- You enabled full transparency which doesn't work without the template
- You are using `cdn.discordapp.com` or `media.discordapp.net` which don't work as a valid url anymore
- The URL is incorrect

## How to make the background work with full transparency
- Open the [template](https://github.com/OasisVee/theme-templates/blob/main/full-transparency-background-template.json)
- Press the download button
- Move the downloaded `.json` to your `Aliucord/themes` folder using a file manager & restart Aliucord if it was open
- Go to Themer settings, enable full transparency & enable the theme
- Go inside the theme settings → `Background` & paste the image url
- Press back, Save changes & restart Aliucord
