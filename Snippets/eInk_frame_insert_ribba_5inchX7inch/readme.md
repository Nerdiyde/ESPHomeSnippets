

# eInk Frame Insert suitable for Ikea Ribba 5″x7″ picture frame

The more you get into the topic of SmartHome, the more you ask yourself how you can bring all this data into your normal life in the most convenient and attractive way possible.

One solution to this problem is my MagicMirror project. I have another one thanks to Madalena (https://github.com/Madelena) when I came across your GitHub repo a few months ago (https://github.com/Madelena/esphome-weatherman-dashboard). 

After expanding the project a bit, I came up with the E-Ink frame insert shown below, which can be used to build a battery-powered E-Ink display that receives the data from a Home Assistant instance.

To simplify the hardware setup a bit, I created a 3D printable insert with which the E-Ink display and the complete electronics can be installed precisely in the Ikea Ribba 5″x7″ frame used.

The STL files are available 
 - [Ikea RIBBA 13x18cm / 5"x7" Frame insert](https://nerdiy.de/en/product-2/eink-frame-insert-suitable-for-ikea-ribba-5x7-picture-frame-3d-printable-stl-files/)
 - [Ikea RÖDALM 13x18cm / 5"x7" Frame insert](https://nerdiy.de/en/product-2/ikea-roedalm-eink-rahmeneinsatz-fuer-13x18cm-5x7-bilderrahmen-3d-druckbar-stl-dateien/)

## Configuration
If you like, use the available example configuration in the "config" folder.

Before you flash it to your frame check the following:
- make sure that the correct GPIOs are set at the top of the configuration
- make sure that the correct display type is set
- make sure the correct timezone is set
- check if you want to uncomment/activate any security features (e.g. passwords, API-keys, etc.)

## Pictures

### RIBBA frame insert
The RIBBA frame uses the FPC2Dupont breakout board which is wired seperately to the MCU. A material list is available [here](https://nerdiy.de/en/product-2/eink-frame-insert-suitable-for-ikea-ribba-5x7-picture-frame-3d-printable-stl-files/)

![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/ribba_insert/1.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/ribba_insert/2.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/ribba_insert/3.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/ribba_insert/4.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/ribba_insert/5.png)

### RÖDALM frame insert
The RÖDALM frame uses the "ePaper Driver Board" made by Seeed. A material list is available [here](https://nerdiy.de/en/product-2/ikea-roedalm-eink-rahmeneinsatz-fuer-13x18cm-5x7-bilderrahmen-3d-druckbar-stl-dateien/)

![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/roedalm_insert/1.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/roedalm_insert/2.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/roedalm_insert/3.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/roedalm_insert/4.png)
![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/roedalm_insert/5.png)

## Available designs
The following designs are intigrated in the example configuration.

### Simple Weather Display

![](https://github.com/Nerdiyde/ESPHomeSnippets/blob/main/Snippets/eInk_frame_insert_ribba_5inchX7inch/images/designs/1.png)

## Trademarks

All third-party trademarks are the property of their respective owners. More infos here: https://nerdiy.de/en/warenzeichen/  

## License

Unless otherwise stated, all works presented here and on Nerdiy.de that are not based on software/code are subject to the CC BY-NC-SA 4.0 license (attribution - non-commercial - dissemination under the same conditions 4.0 international).

You can find additional infos here: https://nerdiy.de/en/lizenz/
