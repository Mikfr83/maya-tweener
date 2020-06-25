# Tweener <img src="icons/tweener-icon.svg" width="32px" height="32px">

<p align="center">
<img src="tweener-screenshot.png" width="50%" height="auto">
</p>

Tweener has nothing to do with young people, basketball or [that tennis move between your legs](https://en.wikipedia.org/wiki/Tweener_(tennis)).

Instead, Tweener is a tool similar to TweenMachine or aTools/animBot. It allows you to quickly create in-betweens or adjust 
existing keys by interpolating towards adjacent keyframes, and can speed-up your workflow when creating breakdowns and 
in-betweens.

I am an animator myself and so I very much tailor the tool to my own needs.

## Requirements

Maya 2017 Update 3 or later.

## Installation

Download <a href="https://github.com/mortenblaa/maya-tweener/raw/master/tweener-install.py" download>tweener-install.py</a> (right-click, save link as...) and drag 
the file into Maya's viewport. Make sure it is a `.py` file and not a `.txt` file.

If you prefer to manually install the plug-in, refer to "Installation" page in the [wiki](https://github.com/mortenblaa/maya-tweener/wiki).

## Documentation

Please refer to the [wiki](https://github.com/mortenblaa/maya-tweener/wiki).

## Getting Started

After installing Tweener, click the shelf button <img src="icons/tweener-icon.svg" width="32px" height="32px">

Alternatively, you can execute `tweener` as a MEL command.

Tweener is quite simple. Select the tween mode and drag the slider to interpolate between poses. I'll encourage you to 
explore each type. See the description of each mode below.

![demo](tweener-demo.gif)

### Blend Modes

| Icon | Mode | Description |
| :---: | :--- | :--- |
| <img src="icons/between.svg" width="20" height="20"> | Between | Interpolates between two adjacent keys, ignoring the current key. |
| <img src="icons/towards.svg" width="20" height="20"> | Towards | Interpolates towards two adjacent keys based on the current key. |
| <img src="icons/average.svg" width="20" height="20"> | Average | Interpolates towards the average value of the selected keys. |
| <img src="icons/curve.svg" width="20" height="20"> | Curve | Interpolates along the curve formed by the two adjacent keys' tangents. |
| <img src="icons/default.svg" width="20" height="20"> | Default | Interpolates towards or away from the default value of each attribute. |

### Additional Buttons

| Icon | Name | Description |
| :---: | :--- | :--- |
| <img src="icons/overshoot.svg" width="20" height="20"> | Overshoot | Extends the interpolation from `[-100:100]` to `[-300:300]` and allows you to go past the target. |
| <img src="icons/keyhammer.svg" width="20" height="20"> | Key Hammer | Adds a key for every attribute for any key on selected objects. The manual equivalent method would be to go to the first key and press `S`, go to the next keyframe and press `S`, go to the next keyframe and press `S` etc. for every keyframe. |
| <img src="icons/tick-special.svg" width="20" height="20"> | Special Tick Color | Sets the current frame, selected keys, or time range to the special keyframe tick color. |
| <img src="icons/tick-normal.svg" width="20" height="20"> | Normal Tick Color | Sets the current frame, selected keys, or time range to the normal keyframe tick color. |

## Known Issues

Please refer to the [issues](https://github.com/mortenblaa/maya-tweener/issues) page for known issues.

## Licensing

Tweener is licensed under the **GNU General Public License v3.0**. See the [license file](LICENSE) for more information.

## Support Development

If this tool brings you joy, you can share it with your friends or buy me a coffee with the button below.  

<a href="https://www.buymeacoffee.com/O6Q5vN9" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="51px" width="217px"></a>

Knowing that someone finds it useful greatly motivates me :)
