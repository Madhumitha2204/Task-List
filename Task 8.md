## Python code to print linux distribution name and kernel version:

      import platform
      Print("OS Name : " +platform.system()) #Print operating system name
      print("OS Distribution :"+platform.dist()[0]) #print distribution name
      print("OS Architecture:"+platform.machine()) #print OS Architecture
      print("OS Version :"+platform.release()) #Print OS version
      print("Details about Os;"+platform.platform"()) #print OS Details
      print("python compiler version:"+platform.python_compiler()) #print compiler version
      Print("Machine name:"+platform.node()) #print machine name
     

**Flow Chart:**
Step 1: The first Line of `import platform` in that the platform is used to access the hardware ,operating system and interpreted version information.
Step 2:Using this if i want to find out the python version simply add `platform.python version()`
Step 3:Using this technique only to find out the linux distribution i has simply add `platform.dist()`
