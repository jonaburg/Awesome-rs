<h1 align="center">What is that?</h1>
<p align="center">
  <i>AwesomeWM but oxidized and rewritten as Wayland Compositor</i>
</p><br>

Awesome-rs is supposed to replace (currently archived) project called [way-cooler](https://way-cooler.org/), which tried to be "AwesomeWM for Wayland" like this one.
<br></br>

## Why?
Awesome is really great X11 Window Manager but there are few problems related mostly to X11 itself.

Xorg provides only Software Rendering and requires external Compositor (xcompmgr, compton or picom) to re-draw everything on screen which makes it less performant and more buggy than we want it to be.

## Project design
- Compatibility with X11 version
- Extend Awesome API with Wayland specific features
- Layershell backend for widgets and `awful.wallpaper`
- Extend Awesome from Window Manager to Display Server nad Compositor

## License
Awesome-rs is licensed under GNU Public License v3
