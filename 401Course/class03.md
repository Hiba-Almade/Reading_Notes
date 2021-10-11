# Maps, primitives, File I/O:

## java type system:
`>>` Java has two types of system:
*  Alternatives such as int , boolean .. this type is accessed quickly

* Reference types such as Integer, Boolean. Its access is slower

`>>` The choice of type depends on the size of the application and available memory

- Each type of data holds a different size in memory:
* boolean – 1 bit
* byte – 8 bits
* short, char – 16 bits
* int, float – 32 bits
* long, double – 64 bits

* Boolean – 128 bits
* Byte – 128 bits
* Short, Character – 128 bits
* Integer, Float – 128 bits
* Long, Double – 192 bits


`>>` Alternatives variables are better to use but Java is not allowed to use them in the Genics and Reflection API

### performance:
The performance of Java programs is highly dependent on the device it is running on and the compiler used

## java exception:

An error occurs during program execution that disrupts its normal functioning

`>>` The error is transferred to the exception handler trying to find a way to complete the work and correct the error, if it does not find the program stops

`>>` One of the methods used to avoid program crashes and to detect and correct errors **TRY - CATCH**

---

### Scanning:

When we need input from the user or from file, as the simplest solution we use Scanning
