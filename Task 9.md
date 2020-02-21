## Python code using function, file input and print each line with line number in the terminal.

To Open the file

    f=open('file_name','r')
 This variable for to count and print the number of lines
 
    num=1
To read all lines

    f.readlines()
   Its return list(For understanding similar to ARRAY data type each array memory only have a single line of data in the file)
   Get the data from the list by one by one

    For data in f.readline():
    Print(str(num)+" "+data)
    num=num+1
   
why i am using `str()` function means the `num()` have integer value but data have string value we want to print the num and data in same line concatenate the num and dataa we can't concatenate the integer datatype and string datatype so we use convert integer to string data type.
