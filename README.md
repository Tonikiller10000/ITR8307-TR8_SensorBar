# ITR8307-TR8_SensorBar
## An 8 sensor sensor bar using ITR8307-TR8 SMD sensors.
The sensor bar was made with the ITR8307-TR8 smd sensors on only one PCB layer and was meant to be used in the Linefollower project to detect a black line on the white surface. 

<img src="https://github.com/Tonikiller10000/ITR8307-TR8_SensorBar/blob/main/SensorBar_Pictures/bar1.jpg"/>
<img src="https://github.com/Tonikiller10000/ITR8307-TR8_SensorBar/blob/main/SensorBar_Pictures/se1.png"/>

### How it works:

<table>
  <tr>
    <td><img src="https://github.com/Tonikiller10000/ITR8307-TR8_SensorBar/blob/main/SensorBar_Pictures/IR1.png"/></td heigth=300>
    <td> The ITR8307 sensor contain an IR led witch send`s infrared ligth to an object and it`s recived back by an IR photoresistor with witch it can calculate the distance between the surface and the sensor.</td>
  </tr>
 </table>

With an 220R resistor to the internal IR LED and an 10K resistor to the photroresistor to create an voltage devider, the sensor return values from 0 to 5v in function of the distance between the sensor and the object. 

Schematic:
<img src="https://github.com/Tonikiller10000/ITR8307-TR8_SensorBar/blob/main/SensorBar_Pictures/se.png"/>

Links:
- ITR8307-TR8: https://pdf1.alldatasheet.com/datasheet-pdf/view/105612/EVERLIGHT/ITR8307.html
- Code for testing: https://github.com/Tonikiller10000/ITR8307-TR8_SensorBar/tree/main/SensorBarTesting
- Assenmbly: https://github.com/Tonikiller10000/ITR8307-TR8_SensorBar/blob/main/SensorBar_Pictures/assembly1.jpg
















