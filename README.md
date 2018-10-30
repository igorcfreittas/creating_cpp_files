# Automating File Creation For C ++

### :pushpin: It is a Shell Script made to create files for the programming language C++, is used in systems based on linux.

###### OS: Ubuntu 18.04 bionic
###### bash --version: GNU bash, version 4.4.19(1)-release

**To Begin**

1. Save the file "newcpp" to your preferred directory
2. Do not put ".sh" extension in the file
3. Open your .bashrc file located in `/home/user`
4. Go to the end of the file and add in the last line: 
    - `export PATH=/home/your/path/to/script`
    - Do not add the file to the end, only the path
5. Run the command in the .bashrc directory: `source .bashrc`
6. _Finished, now you can use it in any directory_

Note: When you run the command, it checks if there is an equal file in the current directory, it asks if you want to delete the old one, if it deletes the old file and creates a new one, creating a new file it will show the file name and path in which it was created.