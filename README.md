# parsing_xml-file-and-creating-excel-sheet
using python xml and xlsxwriter module

# parsing_xml-file
We have used (module) xml for parsing the document which contains four sub-packages:
Dom, parsers, sax, etree, we have used the etree(ElementTree library) and we have given it an alias name ET.
Then we will pass the compiler.xml file as a parameter to ET.parse. After this we will use getroot() method in order to fetch the root of the xml file which is <catalog>.
Then we have used tag , attrib, text in order to find various elements.
In order to print the attrib and text of a specific book id we have used if else condition on it, and user id is taken as an input from the user the atrrib and text of the book would be printed on the basis of that user input.
# creating-excel-sheet
In order to create an xml file we will use xlsxwriter module for this, then we will use workbook() method which takes one-argument as a filename then the workbook object is used to add new worksheet. We use this work object to write data via the write() method. After this we will create a variable my_list which will store the data.

