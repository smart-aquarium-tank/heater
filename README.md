# Aquarium tank water heater
Using IRF520 MOSFET to turn the DC12V/50W heater on or off.

## Schematic
![schematic](http://qqtrading.com.my/image/catalog/Products/Module/IRF520/CK-1202_LRG.jpg)

## IRF520 MOSFET Specifications
* Input Voltage: 3.3V ~ 5VDC
* Output load voltage: 0-24V
* Output load current: <5A (More than 1A required a heat sink)
* Weight: 10g
* Size: 33.5 x 25.5mm  
  
![irf520](https://14core.com/wp-content/uploads/2015/09/CK-1202_LRG-300x259.jpg)

## Arduino Code
```c
#define heater 6

void setup(void) 
{ 
 pinMode(heater, OUTPUT);
} 
void loop(void) 
{ 
 digitalWrite(heater, HIGH);
} 
```
