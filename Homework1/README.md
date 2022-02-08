Circuit of the LM317-implemented Voltage Regulator

When creating the voltage regulator circuit, the first thing to do is to determine if you want the output voltage to be fixed or adjustable. For this case, the adjustable was chosen and one of them was picked from the list of regulators available to us. The LM317LBZRAG was chosen and all that was left to do is to simply follow the data sheet and use the recommended circuit provided. This included a shunt resistor and two shunt capacitors. The resistor value is 240 ohms. an adjustable resistor of 5k ohms is added to the adjustable terminal of the LM317LBZRAG. The first capacitor is a bypass capacitor with a 0.1uF value, it is used to filter out noise. The second capacitor is a bulk capacitor of a vlaue 1uF meant to handle sudden change in load.

______________________________________________________

Circuit of the LM78-implemented Voltage Regulator

When choosing a fixed voltage regulator we are only looking for a regulator that is not going to change its output. This means that no matter the input, the output will remain as a set fixed voltage. For this case we chose the LM78L05ACZ voltage regulator. It does not require any resistors since after all, the goal is to keep the voltage fixed on the output. The shunt capacitors will remain and as the datasheet stated, and it will be 0.1uF each. Each capacitor will be at both ends of the regulator. One that is bypass and the other is bullk.
