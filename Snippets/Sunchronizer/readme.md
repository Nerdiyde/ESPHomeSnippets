

# Sunchronizer S1 - 400W module solartracker for elevation axis

Since I started working on the successful balcony power plants (here in Germany), I asked myself how the energy yield of the two to four solar modules could be further improved.

The “Sunchronizer S1” is a solar module holder with which “standard” 400W solar modules can automatically track the sun on one axis. As with other projects on Nerdiy.de, the required components consist largely of 3D printed components and standard mechanical parts.

Ultimately, everyone should be able to build their own solar tracker for their solar modules.

The axis is tracked using a 6000N linear actuator, which is controlled via an ESP32 and corresponding electronics. The firmware of the ESP32 is based on ESPHome and can therefore be easily integrated into HomeAssistant or many other SmartHome systems. The Sunchronizer can also be used independently of a connection to other systems. For example, the position can be obtained automatically via a GPS receiver, which means that the current time is also known. Based on this data (and the permanently configured orientation (compass direction) of the Sunchronizer), the optimal elevation angle is then calculated and set. So that this can be set correctly, the angle of the solar module is measured four times per second with an acceleration sensor and adjusted accordingly if necessary.

The STL files, material list and more info is available [here](https://nerdiy.de/en/product-2/sunchronizer-s1-400w-solar-tracker-for-elevation-axis-3d-printable-stl-files/).


![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/11.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/12.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/1.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/2.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/3.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/4.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/5.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/6.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/7.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/8.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/9.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/Sunchronizer/images/10.png)

### Trademarks

All third-party trademarks are the property of their respective owners. More infos here: https://nerdiy.de/en/warenzeichen/
  

### License

Unless otherwise stated, all works presented here and on Nerdiy.de that are not based on software/code are subject to the CC BY-NC-SA 4.0 license (attribution - non-commercial - dissemination under the same conditions 4.0 international).

You can find additional infos here: https://nerdiy.de/en/lizenz/
