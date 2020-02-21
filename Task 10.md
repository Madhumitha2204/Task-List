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
                         

