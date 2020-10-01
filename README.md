# Python CLI for exporting a Linux system's user information

Practice Python tool to export a system's user information created during LA course.  
Purpose of this tool is to export a system's user information: 
- user names
- IDs
- home directories
- shells

## How to use?



Possible formats are JSON or CSV. 
By default, script will display JSON formated data to the console.  
```--format``` flag allows user to export data in csv format.  
```--path``` flag defines the path to output file.  
 
Examples:
```
$ hr --format=csv --path=path/to/users.csv
$ hr --path=path/to/users.json
$ hr
```

Sample output:  
```
  {  
    "name": "aleksandar",  
    "id": 1034,  
    "home": "/home/aleksandar",  
    "shell": "/bin/bash"  
  }  
  ```
