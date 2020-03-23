# Excel-To-Json-Jar
Convert any Excel to json

# How to run

java -jar ExcelToJson-0.1.1.jar -s C:\Users\soham\Downloads\Financial_Sample.xlsx -d C:\Users\soham\Downloads</br>

java -jar E:\ExcelTOJson\ExcelToJson-0.1.1.jar -s C:\Users\soham\Downloads\Financial_Sample.xlsx -d C:\Users\soham\Downloads</br>


Ex : java -jar jar_location -s source_file_location -d destination_file_location</br>


OPTIONS:</br>
Source file may not be empty.</br>
usage: java -jar excel-to-json.jar</br>
 -?,--help <arg>          This help text.</br>
 -d,--destination <arg>   The destination directory where the output.json should be created.</br>
 -df,--dateFormat <arg>   The template to use for formatting dates into strings.</br>
 -empty                   Include rows with no data in it.</br>
 -fillColumns             To fill rows with null values until they all have the same size.</br>
 -l,--rowLimit <arg>      Limit the max number of rows to read.</br>
 -n,--maxSheets <arg>     Limit the max number of sheets to read.</br>
 -o,--rowOffset <arg>     Set the offset for begin to read.</br>
 -percent                 Parse percent values as floats.</br>
 -pretty                  To render output as pretty formatted json.</br>
 -s,--source <arg>        The source file which should be converted into json.</br>
