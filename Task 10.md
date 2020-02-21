## Python using class (atleast 3 function inside) and a dictionary:

    class file:
    def __init__(self,filename): # intialize the object
         print(filename+" File is OPEN") #print the given details
         self._file= open(filename,'r+') #result in string value
    def file_read(self):#reading the content of file
        return self._file.read()
    def file_write(self,data):
        self._file.write(data)
        print("File is updated")
    def save(self)
        self._file.close
        print("File is save and close")
     file_data={
    "file_name":"main.py",
    "write_data":[
    "#test1\n",
    "#test2\n",
    "#test3\n"
    ]
    }
    _file= file(file_data["file_name"])
    print(_file.file_read())
    for data in file_data["write_data"]:
    _file.file_write(data)
    _file.save()()
    
**Flow chart:**

 - Step 1:  Keyword  `def`  marks the start of function header. A
   function name to uniquely identify it.the next line print the file
   name as "file is open".
 - Step 2:`self._file= open(filename,'r+')` used to return the string  value.
 - Step 3 :`def file_read(self)` used to read the given content of the file.
 - Step 4:Then the `self._file.write(data)` used to write the content in the file.
 - Step 5: `self._file.close` automatically closes a file when the reference object of the file reassigned to another file.
Step 6:Save the file as main.py








                         

