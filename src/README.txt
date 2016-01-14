netIDs: at200 blz4 myk3 ra102

Readability
Bins.java
No commenting for clarification, would be incredibly useful for the sections which are used for producing disks, placing items into disks, and similarly less apparent sections

Disk.java
Well commented and far easier to understand on simple level

Testability 
Testing with inputs that do not fit the proper input (such as strings) can be input to the scanner is important and ensure the code operates under unexpected conditions.
Break statements and closing input streams is important for making the program flexible while also preventing memory leaks.

Input to test for working under improper input… “1 2 3 4 xyz”

Extensibility
The system includes a lot of redundant .print commands and would benefit from these being shortened to single commands with /n
Several functions in Disk.java feature bulky, redundant if/else statements which can be easily simplified