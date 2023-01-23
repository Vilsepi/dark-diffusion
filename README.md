# Dark Diffusion

A simple dark theme for [Stable Diffusion WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui). Designed to declutter the interface to focus attention on the image content. Developed for Chrome & Windows 11 on a 4k resolution.

![](screenshot.jpg)

## Installation

Copy `user.css` to the root directory of your [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) installation.

Launch your WebUI with argument `--theme=dark`. For example, on Windows your `webui-user.bat` should include:

    set COMMANDLINE_ARGS= --theme=dark

## Known issues / work-in-progress

- Sliders have pretty broken style
- Unchecked checkboxes have default dark blue background
- Interrupt/Skip button have red color but blue border
- Gallery background is transparent in some cases, showing underlying images

## Acknowledgements

[Dark-Themes-SD-WebUI-Automatic1111](https://github.com/Nacurutu/Dark-Themes-SD-WebUI-Automatic1111) used as a starting point for this theme.
