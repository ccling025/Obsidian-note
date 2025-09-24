# Use GDB
### 1.Recompile the file
```bash
  gcc -g -o volume volume.c
```
### 2.Open GDB
```bash
  gdb ./volume
```
### 3.Set break point
```bash
  b main //break at main function
  b 11 //break at line 11
```
### 4.Move on 
  - 1.next           *without going into function
  - 2.step           *go into function
  - 3.continue  *directly go to break point

### 5.Quit
