# Lipo_2S_charge_indicator

Bargraph displaying charge status of a 2S lipo battery

Voltage levels inspired by https://blog.ampow.com/lipo-voltage-chart/ LiFePO4 levels: https://powmr.com/blogs/news/lifepo4-voltage-chart-and-soc#gf

Voltage level are conservative so that battery life is preserved

First led is always on even is battery is weak, 4 other leds will indicate charge status.

Voltage levels are: 7.4V  7.6V  7.9V  8.2V   respectively for LiFePO4:  6.1V   6.5V   6.6V   6.7V

If voltage is < 7.4V  (Only first led ON) -> must stop operation otherwise battery life will be shortened, this threshold can be adjusted by changing the value of R2

If voltage is > 8.2V (All leds ON) -> full: no need to recharge more, this threshold can be adjusted by changing the value of R1

The LM3916 needs +12V to operate, therefore a step-up converter had to be added to the design

![Photo](Documents/component_side.jpg)

The indicator is monitoring the batteries of this little guy

![Photo](Documents/Robot.jpg)

How it is wired using 22AWG type wire

![Photo](Documents/solder_side.jpg)
