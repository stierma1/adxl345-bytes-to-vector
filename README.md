# adxl345-bytes-to-vector
Converts the adxl345 bytes to a 3d vector

Input
X LSB  
X MSB

Y LSB
Y MSB

Z LSB
Z MSB

Output
X int
Y int
Z int


```javascript

var adxl345Bytes2Vec = require("adxl345-bytes-to-vector");
var rawBytes = [0x31,0x00,0x23,0x00,0x31,0xff];
var vector = adxl345Bytes2Vec(rawBytes);
//vector = [ 49, 35, -207 ]

```
