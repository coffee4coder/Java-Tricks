# How to convert a double/float to integer in java

_Let’s say that the double variable x holds the value 3.6987 and needs to be converted to an int. There are two ways that this can be done:_

### 1. All the digits after the decimal are lost and x holds the integer 3; this can be done using typecasting in Java.

### 2. The value is rounded off to the nearest integer (i.e.,3.6987 is rounded off to 4); this can be done using the Math.round() function in Java.​


* #### Typecasting:
   #### Since double is a bigger data type than int, it needs to be down-casted. See the syntax below:

   - #### Structure: (int datatype) variable name = (int) (Double datatype);

   ```Java
   int IntValue = (int) DoubleValue;
   ```
