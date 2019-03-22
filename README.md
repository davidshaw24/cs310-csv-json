# cs310-csv-json

This project is a CSV-JSON converter. It takes data formatted in either format and converts
it to the other format. It works both ways. CSV stands for "Comma-Seperated Values". CSV is
used to represent tabular data. JSON stands for "JavaScript Object Notation". It is used 
as a general-purpose format for many kinds of data, particularly Web-based applications. 
My instructor gave me the skeleton code for this project and only had me complete two methods
in the Converter.java file. These methods are csvToJson() which converts a CSV string into
the corresponding JSON string, and jsonToCsv() which converts a JSON string into the 
corresponding CSV string. This project was written in Java.

# Prerequisites

NetBeans 8 IDE most preferably 8.2
Current installation of Git on your machine
Recent version of JDK installed on your maching

# Installing

Fork the GitHub repository and clone it to your device using the Git client built into the
NetBeans IDE. 

When you create the project in NetBeans, use the "Java Project with Existing Sources"
option.

Download and install the OpenCSV and json-simple libraries. The installation is a 
two-part process: the first part is to copy the library files into your JDK, and 
the second part is to add them as libraries in NetBeans.

Finally, check the NetBeans project that you cloned from GitHub to ensure that the 
necessary libraries are included in its classpath.

 In the NetBeans project tree, right-click the project name ("cs310-csv-json"), select 
 "Properties", and in the "Project Properties" tree, choose "Libraries" from the list 
 of categories.  Ensure that there are four compile-time libraries added to the project: 
 OpenCSV, json-simple, JUnit 4.x, and Hamcrest 1.x (Hamcrest is a framework for writing 
 "matcher" rules; it is required by JUnit).  If any libraries are missing, click "Add 
 Library" and add them from the list of libraries.
 
 # Testing
 
 To run the unit tests, right-click ConverterTest.java and choose "Run File" from the 
 context menu.  A new output window should appear which displays the results of all four
 unit tests.
 
#Authors

David Shaw - JSU student
