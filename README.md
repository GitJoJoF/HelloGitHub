# Try git hub
my first hand at GitHub!
Fine! I've done something!
a long journery!

change on remote
reslove conflict: change on master
solve conflict : change on trybranch

## my try process
```
**local**                                         **remote**
                                                 create: master
changed: master                                  
new: trybranch2                                                                      
                                                 new push: trybranch2
changed: trybranch2                                                                  
                                                 new push: originbranch2
merge: master <= trybranch2                                                          
checkout: originbranch2 <= origin/trybranch2                                         
merge: master <= originbranch2                                                   
delete:originbranch2
                                                 push: master
changed: master
create: rebasebranch
changed: rebasebranch
rebase: rebasebranch => master
changed: master 
create: rebasebranch2
checkout: rebasebranch2
chagned: rebasebranch2
rebase: rebasebranch2 => rebasebranch
rebase: master => rebasebranch
checkout: master
delete: rebasebranch
delete: rebasebranch2
changed: master
                                                push: master
```
