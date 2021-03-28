# RSA-Algorithm-Using-x86-ASM

## Introduction
This project is an implementation of RSA(public key encryption technology) in Assembly Language(x86)

### Prerequisites and Requirements/Configurations for Source Code 
Before you can run the program , you need to : 
    1.Install an IDE and install relevant extensions for x86 MASM.
  
In this case , I have used Microsoft Visual Studio 2019.
 
You can easily download  IDE from :

*Visual Studio 2019 : https://visualstudio.microsoft.com/downloads/

### Configuration:
    1.In the New Project dialog (shown in the image below), select Other Languages, select Visual C++, select General, and then select Empty Project.

    2.Give a name to the project (assume it AssemblyDemo for this tutorial). Now click the OK button.

    3.Now, right-click on your project in solution explorer and select Build Customizations.

    4.Right-click on Source Files in solution explorer & select Add > New Item.

    5.Now go to Utility > Text File to add a new file, but we do not want to add .txt file, instead we want to add a .asm file. So, rename your new text file as Test.asm

    6.Now right-click your project again and click Properties. Now click the tiny arrow marker besides Configuration Properties to expand it. Now click Microsoft Macro Assembler and expand it.

    7.Now click General entry under Microsoft Macro Assembler and then set the value of Include Paths as C:\Irvine. The menu should now like this.

    8.Click Linker tab to expand it. Select General and set the value of Additional Library Directories to C:\Irvine

    9.Click Input, select Additional Dependencies. You will see a list of different .lib file names written there, do not alter any of those. Write irvine32.lib; at the start of the list like this.

#### Program Execution 
  1. Choose an Option whether to encrypt(1) the testcases file or decrypt(2)

  2. If Option 1 is selected , you will be provided with a public key(d) and value of mod (n)
     1.Choose an Option whether to encrypt(1) the testcases file or decrypt(2)

  3. You must remember the keys in order to decrypt the files back to plain text.
     2.If Option 1 is selected , you will be provided with a public key(d) and value of mod (n)

     3.You must remember the keys in order to decrypt the files back to plain text.

  4. If option 2 is selected, program will ask you to input the public key and the value of mod for plain text conversion.
      4.If option 2 is selected, program will ask you to input the public key and the value of mod for plain text conversion.
