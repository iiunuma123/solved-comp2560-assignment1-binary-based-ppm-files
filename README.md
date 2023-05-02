Download Link: https://assignmentchef.com/product/solved-comp2560-assignment1-binary-based-ppm-files
<br>
Write a C program to merge two given binary-based ppm files (P6). The names of the two given image files and the name of the combined image file are given as command line arguments. The combined image is obtained by putting the second image to the top-right corner of the first image. The sizes of the given image files are not fixed. If the width or the height of the first image is less than that of the second, your program should report error.

All these image files can be opened with image viewer tools that can work with ppm file format.

For simplicity, the following restrictions are added to the file format of the input:

<ul>

 <li>no comment line after the file type specification</li>

 <li>width (number of columns) and height (number of rows) formatted as ASCII decimal in the second line</li>

 <li>maximal value of color components given in the third line</li>

</ul>




This is a practice on using System Call I/O. You are not allowed to use standard I/O library functions or other graphics related libraries.

Sample input (<u>firework.ppm</u> and <u>150.ppm</u>):










<em>60-256 System Programming                                                                                                            Dr. Chen </em>
















Corresponding output:








