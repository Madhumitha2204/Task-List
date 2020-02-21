## Python code to print linux distribution name and kernel version:

      import platform
      Print("OS Name : " +platform.system()) #Print operating system name
      print("OS Distribution :"+platform.dist()[0]) #print distribution name
      print("OS Architecture:"+platform.machine()) #print OS Architecture
      print("OS Version :"+platform.release()) #Print OS version
      print("Details about Os;"+platform.platform"()) #print OS Details
      print("python compiler version:"+platform.python_compiler()) #print compiler version
      Print("Machine name:"+platform.node()) #print machine name

  
