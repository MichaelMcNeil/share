 ====== dos2unix ======
 ```
cat file | sed "s/^M\{1,\}$//" | sed "$ s/^Z//" > file.new
```
====== unix2dos ======
```
cat file | sed "s/$/^M/" | sed "$ s/$/^Z/" > file.new
```
