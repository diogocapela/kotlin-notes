# kotlin-notes

### Basic
```kotlin
// Variables and Constants
var myVariable = 42
val myConstant = 120

// Data Types
var name:String = "John Doe"
var age:Int = 24
var pi:Float = 3.14f
var ip:Double = 4.3123

// Empty Variables - When null is expected
var foo:String?
var qux:Int?

// Variable can be empty - ?
// Variable cannot be empty - !!

// Read
print("Name:")
var name = readLine()
print("Age:")
// !! - expecting input null
var age:Int = readLine()!!.toInt()
print("PI:")
// !! - expecting input null
var pi:Double = readLine()!!.toDouble()

// Print
print(name)
println(name)

// Template Variables
print("My name is $name")
```
