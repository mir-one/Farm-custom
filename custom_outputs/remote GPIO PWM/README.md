#### Custom Output: PWM Remote GPIO (gpiozero)

[Version 1.1](https://github.com/mir-one/Farm-custom/blob/master/custom_outputs/remote%20GPIO%20PWM/CHANGELOG.md)

By [Roman Inozemtsev](https://mir.one/)

#### About

Remotely control GPIO pin duty cycles over a network with the use of [gpiozero](https://github.com/gpiozero/gpiozero).

#### Requirements

* Farm >= 8.5.0

#### Setup

Read [this](https://gpiozero.readthedocs.io/en/stable/installing.html) and [this](https://gpiozero.readthedocs.io/en/stable/pi_zero_otg.html) for information about setting up your systems to use this Output.

* In Farm, upload the [Custom Output](https://raw.githubusercontent.com/mir-one/Farm-custom/master/custom_outputs/remote%20GPIO%20PWM/farm_custom_output_remote_gpio_pwm.py) file under Configure -> Outputs.
* In Farm, on the Output page, use the dropdown to select and add the new Output "PWM Remote GPIO (gpiozero) (GPIO)".
* Read the notes above the Output settings to configure your systems to use the Output.
