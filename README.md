# Lipo_2S_charge_indicator

Bargraph displaying charge status of a 2S lipo battery

Voltage levels inspired by https://blog.ampow.com/lipo-voltage-chart/

Voltage level are conservative so that battery life is preserved

If voltage is < 7.4V  -> must stop operation otherwise battery life will be shortened

If voltage is > 8.15V -> full: no need to recharge more

The LM3916 needs +12V to operate, therefore a step-up converter had to be added to the design

![Photo](Documents/component_side.jpg)
