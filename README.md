# GCC-FIND  
gccfind.sh is a script in bash, which gets the following arguments:  
1. **a path to a directory (relative or a full path).**    
  * we can assume the directory does exists, and doesn't contain any spaces in its name *  
2. **an ordinary word.**    
  
the script **deletes** all the compiled files in the directory (all of the .out files), then **compiles** only the c files (can
assume they end with .c) that **contains the word** that was given as a second argument.  
if there are c files that doesn't contain that word, they will not get compiled.  
  
there is an option for a **third argument** which is the flag "-r".  
if we choose to write that argument, the script will work also for **sub-directories** as well, and not only for the mentioned directory
which was given as a first argument.  

examples of the script:  
![image](https://user-images.githubusercontent.com/83518959/192657885-a7a187fd-dbb3-4267-af9d-e2c2c560d357.png)  
![image](https://user-images.githubusercontent.com/83518959/192657896-aebc3489-888b-43f0-bec3-b194e9d9728a.png)  



