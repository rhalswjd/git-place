## Git config
- System level : --systemoption. Affects all uses and repositories on the system(administrative)
- Global user level : --globaloption. Affects all repositories of acurrent user
- Local level : --localoption Specific to the current repository

- git init : Initializing a Repository in an Existing Directory
- git satus : Checking Repository Status
- git add file_name : add a new file to be staged
ex) git add . : add all files to staged
- git rm -cached file_name : unstaging a file

## Ignoring a File
- ignore all .a files : *.a
- but do track lib.a, even though you're ignoring .a files above : !lib.a
- only ignore the TODO flies in any directory named build : build/
- ignore doc/notes.txt, but no doc/server/arch.txt : doc/*.txt
- ignore all .pdf files in the doc/directory and any of its subirectories : doc/**/*.pdf

## Commit
- git commit -m "comit message"