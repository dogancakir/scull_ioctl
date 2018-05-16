    1. INTRODUCTION
In this project we converted to text data. These encoding types are UTF-8, UTF-16, UTF-32, ISO8859-1, ISO8859-9.


    2. DEVELOPMENT & OPERATING ENVIRONMENT
		The project is compiled in Linux Lubuntu 13.04, 32 bit version.. Geany used as an editor.

    3. PREPARATIONS
We hold a base encoding type. This encoding type  is unicode. We are converting to unicode for each encoding types. After that, we convert this unicode desired encoding type.

Note : This project is not completed. We did all of the convertion for above encoding types. That convertion functions supplly hexadecimal for each encoding types but it is not working correctly. Because, we didn’t change ioctl in the scull and we add this functions to scull in read and write functions. This convertion functions are below.