# ChillFrames
[![Download count](https://img.shields.io/endpoint?url=https://vz32sgcoal.execute-api.us-east-1.amazonaws.com/ChillFrames)](https://github.com/MidoriKami/ChillFrames)

Chill Frames is a XivLauncher/Dalamud plugin.

This is a very simple utility plugin that allows you to conditionally enable a framerate limiter ingame.

## Why is this useful?

This plugin allows you set a frame limiter for the parts of the game that aren't that important to have constantly running at a high framerate.
When your framerate isn't limited your GPU is using maximum power, generating maximum heat, for minimal visual impact.

For those that game on a mobile laptop this will also allow you to save significant battery as well.

## How does it work?

This plugin hooks into the games renderer and delays frame rendering to generate the user specified framerate.

The delay happens *after* the games default logic, and will only act to reduce framerates.

This means if you have the games settings to reduce the framerate when afk, that setting will still apply and will take priority over the delay Chill Frames causes.

## Configuration Window

The various options allow you to turn off the frame limiter (that is, to have maximum fps) under specific conditions.

For example, if you want maximum fps while crafting you would check `Disable during Crafting`

General Configuration             |  Blacklist Configuration
:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/9083275/220265664-bfa7f456-dd9b-4f8b-88fd-e351a61d649c.png)  |  ![image](https://user-images.githubusercontent.com/9083275/220265612-b7d9439a-ae56-461a-a794-2b24d7df27a6.png)

## Testimonials

![image](https://user-images.githubusercontent.com/9083275/159103862-54542bbb-6dd4-49ef-a7fb-358e9e116ca9.png)
