#### Custom Input: BME680 (Temperature Error Fix)

By [Roman Inozemtsev](https://mir.one/)

Forum Post: [BME680 shows wrong temperature](https://mir.one/forum/general-discussion/sensor-bme680-occasionally-locks-up-and-shows-wrong-temperature-but-correct-humidity-until-deactivated-and-reactivated/)

#### About

A user with the BME680 sensor experienced an issue where the temperature would erroneously and continuously measure 34.54 C until the Input was deactivated and activated again. Since We don't know if this is an isolated incident because we only have one sensor to test, this module was created to fix the issue. If there are more reports of this occurring with other BME680 sensors, this module may move into the built-in set for Farm.

#### Setup

* In Farm, upload the .py file under Config -> Inputs.
* In Farm, on the Data page, use the dropdown to select and add the new Input "BME680 (Temperature Fix)".
