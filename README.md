## RAST

This package contains a jar file which checks the given code satisfies CERT coding standard. rast.jar is used to process large number of source code written in java. It won't compile and generate the class file, it will only verifies the coding standard violation. So input should be an error free(completed successful compilation) java file.


 
 

## Dependency

Compiled on 

```
openjdk version "1.8.0_45-internal"
```

## Project Structure

* Download the .tar file of latest version from here and unzip the file
* The project file contains three directories.
* config - which contains all the configuration files.
* Sample - which contains some examples of both noncompliant and complaint code.
* output - contains the errorlog file
* rast.jar - which is the actual executable file of the project.
* Before running verify all the four are present.
 

## How To use

Open terminal and type
```
rast-h
```
You will get man page

For detailed information please go to the [wiki page](https://github.com/rahulbpkl/rahul_audit_tool_draft-1/wiki)

 
# rast_src
