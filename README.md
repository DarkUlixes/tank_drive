# Simple tank drive arduino code.
This code is made useful when uploaded to an arduino featuring
a USB Host shield connected to a wireless Xbox controller.

The very same code is useful also for wired controller but you need to include the wired library.

###### Connect the defined pins to a double H-Bridge. Assuming the motors are facing each other connect them in order for:

* the lowest pin to drive one motor forward
* the second pin to drive one motor backwards
* the third pin to drive the other motor forward
* the fourth pin to drive the other motor backwards.


###### This can be achieved by good old testing or more easily by connecting:

* the first pin of the first motor to the first output of the first H-Bridge
* the second pin of the first motor to the second output of the first H-Bridge
* the first pin of the second motor to the second output of the second H-Bridge
* the second pin of the second motor to the first output of the second H-Bridge
