# Auto Reload  
###### _reload stuff when things happen_  

```bash
./
├── README.md
├── msg/
│  ├── err/
│  │  ├── dir_not_found
│  │  └── leaf_not_found
│  └── found
└── test/
   ├── is_dir*
   └── is_leaf*
```  

### Synopsis  
Watch for events to run tests which call messages and activate hooks to restart programs or binaries  

__TODO:__  
 - tests  
   - [x] test for regular file  
   - [x] test for directory  
###### \# these are things auto_reload should watch for  
 - [ ] events
###### \# root folder indicate success messages subfolders indicate error or otherwise  
 - messages
   - [x] found  
     - indicates that the argument matches the query (file or directory)  
   - [x] err/dir_not_found  
     - indicates that the argument is not a directory  
   - [x] err/leaf_not_found  
     - indicates that the argument is not a regularfile  
