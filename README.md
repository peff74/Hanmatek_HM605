# HM605 

The HM605 is a very practical and cheap power supply manufactured by etommens and sold through Hanmatek OEM.
It is very easy to use and has a fairly low ripple voltage.
And with a few simple steps, you can make it Modbus enabled.  



## Script Details

The script includes the following functions:

- `setupDS18b20()`: Initializes the DS18B20 sensor and verifies its presence.
- `printAddress(byte addr[8])`: Prints the sensor's address in hexadecimal format.
- `startMeasurementDS18b20()`: Starts a new temperature measurement.
- `checkBusyDS18B20()`: Checks if the sensor is still busy with the measurement.
- `getDataDS18B20()`: Retrieves and processes the temperature data once the measurement is complete.


## Example Output

    Found device with address: 28:FF:4C:60:92:16:05:5C
    Sensor is a DS18B20
    Measurement started
    Measurement completed
    getDataDS18B20 execution time: 498 ms
    Temperature: 22.52 C
