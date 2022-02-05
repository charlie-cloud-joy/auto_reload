# auto_reload  
_reload stuff when things happen_  

```bash
./
└── README.md
```  

### Synopsis  
Watch for events to run tests which call messages and activate hooks to restart programs or binaries  

__TODO:__  
 - tests  
   - [ ] test for regular file  
   - [ ] test for directory  
###### \# these are things auto_reload should watch for  
 - [ ] events
###### \# root folder indicate success messages subfolders indicate error or otherwise  
 - messages
   - [ ] found  
     - indicates that the argument matches the query (file or directory)  
   - [ ] err/dir_not_found  
     - indicates that the argument is not a directory  
   - [ ] err/leaf_not_found  
     - indicates that the argument is not a regularfile  
