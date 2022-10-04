My first readme
root@1eaf9fa2c4c8:/# cd alx-zero_day                                     
root@1eaf9fa2c4c8:/alx-zero_day# echo 'My first readme' > README.md      
root@1eaf9fa2c4c8:/alx-zero_day# README.md                               
bash: README.md: command not found                                       
root@1eaf9fa2c4c8:/alx-zero_day# ls                                      
README.md                                                                
root@1eaf9fa2c4c8:/alx-zero_day# cat README.md                           
My first readme                                                          
root@1eaf9fa2c4c8:/alx-zero_day# git config --global user.email "ojoolato
miwa@gmail.com"                                                          
root@1eaf9fa2c4c8:/alx-zero_day# git config --global user.name "ngskylark
"                                                                        
root@1eaf9fa2c4c8:/alx-zero_day# git add .                               
root@1eaf9fa2c4c8:/alx-zero_day# git commit -m 'My first commit'         
[master (root-commit) abb42b6] My first commit                           
 1 file changed, 1 insertion(+)                                          
 create mode 100644 README.md                                            
root@1eaf9fa2c4c8:/alx-zero_day# git push                                
Enumerating objects: 3, done.                                            
Counting objects: 100% (3/3), done.                                      
Writing objects: 100% (3/3), 235 bytes | 235.00 KiB/s, done.             
Total 3 (delta 0), reused 0 (delta 0)                                    
To https://github.com/ngskylark/alx-zero_day.git                         
 * [new branch]      master -> master                                    
root@1eaf9fa2c4c8:/alx-zero_day# 
asss 3
/alx-zero_day# mkdir 0x03-git                          
root@1eaf9fa2c4c8:/alx-zero_day# ls                                      
0x03-git  README.md                                                      
root@1eaf9fa2c4c8:/alx-zero_day# cd 0x03-git                             
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git#  echo 'My first readme' > READM
E.md                                                                     
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# ls                             
README.md                                                                
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# git add .                      
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# git commit -m 'My first commit'
[master f8b9631] My first commit                                         
 1 file changed, 1 insertion(+)                                          
 create mode 100644 0x03-git/README.md                                   
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# git push                       
Enumerating objects: 3, done.                                            
Counting objects: 100% (3/3), done.                                      
Delta compression using up to 2 threads                                  
Compressing objects: 100% (2/2), done.                                   
Writing objects: 100% (2/2), 274 bytes | 274.00 KiB/s, done.             
Total 2 (delta 0), reused 0 (delta 0)                                    
To https://github.com/ngskylark/alx-zero_day.git                         
   abb42b6..f8b9631  master -> master                                    
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# mkdir bash c js                
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# ls                             
bash  c  js  README.md                                                   
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# touch c/c_is_fun.c js/main.js j
s/index.js                                                               
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# ls                             
bash  c  js  README.md                                                   
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# echo '#!/bin/bash' 'ALX' > bash
/alx                                                                     
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# ls                             
bash  c  js  README.md                                                   
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# cd bash                        
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git/bash# ls                        
alx                                                                      
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git/bash# cat alx                   
#!/bin/bash ALX                                                          
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git/bash# cd ..                     
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# echo '#!/bin/bash' 'School' > b
ash/school                                                               
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# ls                             
bash  c  js  README.md

bash  c  js  README.md                                                   
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# cd bash                        
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git/bash# ls                        
alx  school                                                              
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git/bash# cat school                
#!/bin/bash School                                                       
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git/bash# git add .                 
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git/bash# git commit -m “Starting to
 code today, so cool”                                                    
error: pathspec 'to' did not match any file(s) known to git              
error: pathspec 'code' did not match any file(s) known to git            
error: pathspec 'today,' did not match any file(s) known to git          
error: pathspec 'so' did not match any file(s) known to git              
error: pathspec 'cool”' did not match any file(s) known to git           
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git/bash# git commit "Starting to co
de today, so cool"                                                       
error: pathspec 'Starting to code today, so cool' did not match any file(
s) known to git                                                          
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git/bash# cd ..                     
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# git add .                      
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# git commit-ing to ing to code t
oday, so cool"                                                           
error: pathspec 'Start-ing to code today, so cool' did not match any file
(s) known to git                                                         
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# git commit -m "Starting to code
 today, so cool"                                                         
[master 883396f] Starting to code today, so cool                         
 5 files changed, 2 insertions(+)                                        
 create mode 100644 0x03-git/bash/alx                                    
 create mode 100644 0x03-git/bash/school                                 
 create mode 100644 0x03-git/c/c_is_fun.c                                
 create mode 100644 0x03-git/js/index.js                                 
 create mode 100644 0x03-git/js/main.js                                  
root@1eaf9fa2c4c8:/alx-zero_day/0x03-git# git push                       
Enumerating objects: 11, done.                                           
Counting objects: 100% (11/11), done.                                    
Delta compression using up to 2 threads                                  
Compressing objects: 100% (5/5), done.                                   
Writing objects: 100% (9/9), 659 bytes | 26.00 KiB/s, done.              
Total 9 (delta 0), reused 0 (delta 0)                                    
To https://github.com/ngskylark/alx-zero_day.git                         
   f8b9631..883396f  master -> master  
root@1eaf9fa2c4c8:/alx-zero_day# git checkout -b update_script           
Switched to a new branch 'update_script' 
