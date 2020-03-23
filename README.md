# Excel-To-Json-Jar
Convert any Excel to json

# How to run

java -jar ExcelToJson-0.1.1.jar -s C:\Users\soham\Downloads\Financial_Sample.xlsx -d C:\Users\soham\Downloads

java -jar E:\ExcelTOJson\ExcelToJson-0.1.1.jar -s C:\Users\soham\Downloads\Financial_Sample.xlsx -d C:\Users\soham\Downloads


Ex : java -jar <jar location> -s <source file location> -d <destination file location>


OPTIONS:
Source file may not be empty.
usage: java -jar excel-to-json.jar
 -?,--help <arg>               This help text.
 -d,--destination <arg>   The destination directory where the output.json
                                          should be created.
 -df,--dateFormat <arg>  The template to use for formatting dates into
                                           strings.
 -empty                             Include rows with no data in it.
 -fillColumns                    To fill rows with null values until they all
                                        have the same size.
 -l,--rowLimit <arg>      Limit the max number of rows to read.
 -n,--maxSheets <arg>     Limit the max number of sheets to read.
 -o,--rowOffset <arg>     Set the offset for begin to read.
 -percent                 Parse percent values as floats.
 -pretty                  To render output as pretty formatted json.
 -s,--source <arg>        The source file which should be converted into
                          json.
