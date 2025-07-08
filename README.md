25/6/2025

 First day of training 

In first day of training, i learned about linux in detail and different types of companies. 
   
Linux is the core of the operating system, responsible for managing hardware resources and providing a platform for other software.

Linux is open source and much better than windows.Linux is known for its stability and security. 
To install Linux on laptops , there are some steps to followed: 
       
       Download Virtualbox 7.1.10
       Download Microsoft c++ visual studio 
       Download ubnut desktop 24.04.2 LTS 

The main difference between Linux and windows is  Linux is free and open source , windows are  not open source. 
Linux considered more secure due to its open-source nature, windows are less secure.
Linux is free of cost , windows are not free of cost.

Then, we discussed about different types of companies.
           
            product based companies 
            service based companies 
            startup companies

After that I learned about Booting and its types 
  
Booting - Booting is the process of starting or resetting a computer.
 It has two main types: 

   cold booting and warm booting. 

Cold booting is starting a computer from a completely powered-off state, while warm booting is restarting a computer that is already on. 

   26/6/2025  Day 2 

  Introduction to Kernel , Shell its types and    different commands
 
Kernel -   In an operating system, the kernel is the core component that acts as a bridge between the hardware and the software.

Shell
 In an operating system, a shell acts as an interface between the user and the kernel, allowing users to interact with the system by executing commands. 

 Types of shell 
      
        Bash - Most common shell
        sh - original shell
        zsh- more features 
        fish- modern, interactive 

 Shell categories 
        1. command line shell
        3. Graphical shell

File System Structure
   
       directory              function 
       / (Root):       The top-level directory, from which all other directories branch out.
     
      /bin:            Contains executable programs .
     
      /boot:            Stores files needed for booting the system, including the kernel.
     
       /dev:            Contains device files that represent hardware devices.
     
       /home:           Personal directories for users. 
     
       /lib:             Contains library files that are used by programs.
   
       /media:            Mount point for removable media like USB drives.
    
       /mnt:             Temporary mount point for file systems.
    
       /opt:            Contains optional apps.
   
       /srv:            Contains data for services provided by the system.
     
       /tmp:            Stores temporary files.
    
      /usr:            Contains user-related programs, libraries, and documentation.
    
      /var:           Stores variable data, such as log files, user tracking data, and caches.  

  commands
  
               Commands           Description                         Syntax
   
               ls               List the contents                     ls(options)

             date          Show the current date and time .           date

             whoami         Display the current username.              whomami    

             cd               change the directory .                  cd[directory]

             mkdir              To create new directory                mkdir directory_name

             cat                Create a list with contents            cat>filename

             touch               create file without content          touch filename

             cp                  copy the files                        cp[source]

             pwd                 print the current working directory       pwd

             whereis              show location of binary ,source         whereis[command]

             whatis               To get brief information about command       whatis[command]
 
 ![VirtualBox_ubuntu_27_06_2025_08_55_27 screenshort](https://github.com/user-attachments/assets/8b6b7586-415c-44a5-b484-eef83136b3c0)


 27/6/2025 Day 3

Dual Booting 
Dual-booting refers to the process of installing and running two different operating systems on a single computer, allowing the user to choose which one to use when starting the machine. 

  BARE METAL INSTALLATION 

  Bare metal installation of linux means installing the operating on a computer's hardware , without any intermediary virtualization software.


VM ware 

vm  ware is a commercial product known for its enterprise - grade  features , performence and comprehensive support .

Partitioning Schemes :
Dividing a hard disk into seperate sections .
Each section acts as an independent disk.
Help organize data and install multiple OS.

 Its Types:

 MBR(MASTER  BOOT RECORD )

 maximum 4 primary partitions . Support upto 2 TB.It stores partition info in one place.It has less flexibility.

 GPT(GUID PARTITION TABLE)

 It supports upto 128 partitions .It supports disks larger than 2 TB.More flexibile.
 
File and directory permissions 

 File permissions are the backbone of Linux security, ensuring that only authorized users and processes interact with your data.

 Types of Commands
          1    chomd (change mode)
          
          1. It is used to change the permissions(read, write, execute) of files or directories.
          syntax - chmod[permission] [filename]*for permission 

          2.  chmod +x filename.sh
                   +x enables execute files.
      
         3. chmod 444 filename.sh
            Gives permissions to read only files.

         4. chmod 644 filename.sh
            It enables permissions only to owner 2.

2  chown- change owner
       
        chown user:group file.txt
        Change the owner to user Change the group to group so that other users in that group can access the file .
        
 ![Uploading chmod +x file.png…]()

![test sh is unwriteable](https://github.com/user-attachments/assets/a84a03b2-f741-4f06-b74d-9de160e99ecd)

![VirtualBox_ubuntu_644](https://github.com/user-attachments/assets/b262ef22-71bb-4072-b595-fa030ea6b1f9)


Redirection

Redirection in Linux means sending the output or input of a command to somewhere else, like a file.
Example: echo "Hello" >day3.txt
redirecting the message 'hello' t file 'day3.txt'

         
           Redirection Operators in Linux
       Type        	Symbol         	Example Command	     
       Output	        >           	echo "Hello" > file.txt      
       Append	        >>          	echo "World" >> file.txt	      
       Input         	<	           wc -l < file.txt	         

![redirection](https://github.com/user-attachments/assets/af6553ed-61eb-40b6-b1d3-5cff6d390ff1)

![Uploading 13 14 redirection.png…]()

 Pipe In Linux 

 Pipe - Take the output of one command and pass it to another command .
 example- You have many files in a folder and you want to see only the file that ends with .sh

     syntax 
     command1|command2
     command1-generates output
     command2- takes that output as input

 ![VirtualBox_ubuntu_ pipe](https://github.com/user-attachments/assets/61097c6a-f20e-4012-8c2b-f4a348baa1cd)

 ![Uploading VirtualBox_ubuntu_pipe multiple file.png…]()
 

Shell programs:

   1. Use of variables:
      ![VirtualBox_ubuntu_29_06_2025_09_05_16](https://github.com/user-attachments/assets/f6b0c4cc-3977-4758-9ec6-6bdf1761a94e)

      
![VirtualBox_ubuntu_29_06_2025_09_06_47](https://github.com/user-attachments/assets/6816110e-e3b0-4578-a513-af0b2800185f)

 2 Multiplication table of any number:
![VirtualBox_ubuntu_multiplication of num](https://github.com/user-attachments/assets/c8c8559c-94a7-47c3-92dc-4fc74928b669)

 ![VirtualBox_ubuntu_29_06_2025_09_18_26](https://github.com/user-attachments/assets/8d5153cb-fc9e-4698-926c-b7e54f0deae4)

3. Compare two Variables
    
     ![VirtualBox_ubuntu_29_06_2025_09_30_49](https://github.com/user-attachments/assets/c5c8d9f6-a69f-4476-b761-9abf6a5e06d6)

   
    ![VirtualBox_ubuntu_29_06_2025_09_58_12](https://github.com/user-attachments/assets/f477c6ec-a02e-48f3-a428-368a155f8a1d)

DAY 4 30/6/2025

File compression 

File Compression in linux , helping to reduce the sizes of files .

Use of File Compression 

Save Storage Space: Compressed file take up less disk space, allowing you to store more data.

Faster transmission : Smaller files transfer more qyickly over networks.

There are several commands available for compressing files ;

 1. Gzip - used to compress file. It reduce the size of files , making them eaiser and faster to store or transfer.It compress the filename and replace it with filename.gz. 

     syntax - gzip filename
 
     e.g- gzip notes.txt creates notes.txt.gz and delete notes.txt

     This command wiil compress notes.txt and create a new file named notes.txt.gz, replacing the original file.

Decompress a File 

To decompress notes.txt.gz weu can use the gunzip command .

gunzip notes.txt.gx

This will decompress the file and remove the .gz extension , restoring the original notes.txt file.

    Keep the Original File Too

    To Compress a file and keep the original , use the -k flag.
    
    gzip -k notes.txt

    Now notes.txt (kept)

    notes.txt.gz (created)

    This will create notes.txt.gz without deleting notes.txt.

Wildcards Command - Matches file Without full names. 

            symbol                   Meaning                               Exmaple                       what it does
              *                  matches zer or more character            ls * .txt                    Lists all files ending with .txt.

              ?                  matches exactly one character            ls file? .txt                Matches files?.txt fileA.txt. etc.

              [abc]              matches one character from set         ls file[123] .txt             Matches file1.txt. file2.txt. etc

              [a-z]              matches any character in range          ls file[a-c] .txt            Matches filesa.txt .fileb.txt etc

   Escaping Characters

   Escaping Character means using a special symbol ( Usually a backslash) before a character to tell the computer to treat that character literally , not as a special or reserved symbol.

         character to Escape            How to Escape                        Purpose/Meaning                                                    Example

         space ()                       Use backslash\ or quotes                To treat space as part of filename or command argument.          file\ name.txt or "filename.txt     

         Backslash(\)                   Use double backslash \\                 To represent a literal backslash                                echo \\ prints \

         Dollar sign($)                 Use backslash \$                        To prevent variable expansion                                   echo\$HOME prints $HOME
          
         Asterisk(*)                    Use backslash\*                         To treat * literally ,not as a wildcard                        ls \*.txt lists files named*.txt literally

         Question mark (?)              Use backslash\?                         To treat ? literally,not as a single character wildcard        ls file\?.txt matches file?.txt literally

          Quotes(" or ')               Use backslash\" or \' inside quotes,     To include quotes in strings                                    echo "He said \"Hi\""
                                       or use different quotes type  

         Brackets ([])                 Use backslash\[and \]                    To treat brackets literally                                     ls file\[1\].txt matches file[1].txt

Quotes

       QuoteType   	        Syntax             	Description                                              	Example
 
      Single quotes        	'text'            Preserves literal value of all characters inside.         	'Hello $USER * ?' outputs exactly Hello $USER * ?
 
      Double quotes        	"text"           Preserves most characters literally, but allows            "Hello $USER" outputs Hello followed by your username
                                          
                                             variable expansion and command substitution 

      Backslash             \char             Escapes the next character to be treated literally

 
DAY 4 30/6/2025

Hardware 

Computer hardware refers to the physical components of a computer that you can see and touch. These components work together to process input and deliver output based on user instructions. In this article, we’ll explore the different types of computer hardware, their functions, and how they interact to make your computer work.

The computer has mainly has two major components:

Hardware
Software

          Hardware Type                         Description                                                     Example
       
       Input Devices             devices allow users to interact with
                                 a computer by entering data or commands.                                      Keyboard, Mouse, Scanner, Trackball                 
                                 These devices convert the input into a
                                 format that the computer can process.  

     
       
       Output Devices            Output devices display the results of tasks given                              Monitor,Printer,Speaker                                  
                                 to the computer in a human-readable form. 
                                                                                                                     

       Storage Devices          Some devices are used for storage purposes                                      CD (Compact disc), Hard Drive(HDD),USB
                                and are known as secondary storage devices.            
           

      Processing Unit           Components that process data and execute instructions                         CPU(Central Processing Unit),GPU(Graphics Processing Unit)

      Memory                    Temporary storage used by the CPU to hold data and instructions               RAM(Random access memory), Cache

     Motherboard               It is the main circuit board inside a computer and                              Motherboard
                               it contains most of the electronic components together.
                               All the components of the computer are directly or
                               indirectly connected to the motherboard


    Power Supply                All of a computer system's parts are powered by a power source.                  PSU(Power Supply Unit)

    Networking Hardware        Devices that connect computers and enable communication                          Network Interface Card(NIC) Router, Switch

MOTHERBOARD

Imagine your computer as a big city, and the motherboard as the main road system connecting all the important buildings—like the CPU (the brain), RAM (the memory), and storage (the library). Without the motherboard, these parts couldn’t talk to each other, and your computer wouldn’t work.A motherboard is the main circuit board inside a computer. 

![WhatsApp Image 2025-07-01 at 6 41 11 AM](https://github.com/user-attachments/assets/8e7b2624-d261-4ede-8a97-f4d965035d2b)

   
     Component           	Description
  
    CPU Socket.         	The slot where the processor (CPU) is installed

    RAM Slots (DIMM)   	Slots for installing memory modules (RAM)

    Chipset	              Manages data flow between CPU, memory, and peripherals
   
     BIOS/UEFI Chip	         Firmware that initializes hardware during boot-up

     Power Connectors	      Connectors for power supply to distribute electricity to components
     
     Expansion Slots.      	Slots (PCI, PCIe) for adding graphics cards, network cards, etc.

     SATA Ports	             Connectors for storage devices like HDDs and SSDs

     M.2 Slots	              Connectors for modern high-speed SSDs

     CMOS Battery	           Powers the BIOS memory to retain settings when the PC is off
 
      USB Headers          	Connectors for USB ports on the front or back panel
     
      Audio Connectors.     	Ports for audio input/output devices
     
     Network Port(Ethernet)  	Connector for wired network connections

 ![WhatsApp Image 2025-07-01 at 6 41 11 AM (1)](https://github.com/user-attachments/assets/9812e660-046c-4d30-9dd5-5468572b2cc7)

wHAT is Cache  Memory:

Cache memory is a small, very fast memory inside the CPU that stores data and instructions the CPU  uses often. 
It helps the CPU Work faster by quickly giving it the information it needs without waiting for slower main memory(RAM).

How RAM IS DIFFERENT FROM CACHE MEMRY;

    Feature             RAM(Random Access Memory)                      Cache Memory
     
     Speed   

 



    



     
     


          
          
 
 
   
              
     
     

