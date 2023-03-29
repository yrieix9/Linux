# TD2 
## Exercise 1 : 
### 1.
```
sudo apt update
```
### 2.
```
uname -a
top
ps
nproc
lscpu
df -h
mount
lsusb
hostname
```
## Exercise 2 :
### 1. 
```
x="piri pimpim"
```

### 2.
```
echo $x
```

### 3. 
```
x+ =" piri pimpom"
```

### 4. 
```
mkdir my_programs
cd my_programs
```

### 5.
```
vim pilou.sh
echo "pilou pilou"

```

### 6.
```
source pilou.sh
```

### 7.
```
chmod u+x pilou.sh
```

### 8.
```
./pilou.sh
```

### 9.
```
echo $PATH
```

### 10.
```
PATH=$PATH:$(pwd)
```

### 11.
```
export PATH
```

### 12.
```
cd ~
```

### 13.
```
./pilou.sh
```

### 14.
```
vim .profile
PATH=$PATH:$(pwd)
```

### 15.
```
./pilou.sh
```

## Exercise 3

### 1.
```
vim say_hello.sh
echo "$(date) - Hello" >> hellos.txt
```

### 2.
```
chmod +x say_hello.sh
```

### 3.
```
crontab -e
* * * * * ~/say_hello.sh
```


## Exercise 4

### 1.
```
mkdir hash_checksum
cd hash_checksum
```

### 2.
```
touch .sensible_addresses
touch .sensible_passwords
```

### 3.
```
ls -a
```

### 4.
```
echo "Have a good day" >gentle_script.sh
```

### 5.
```
chmod +x gentle_script.sh
./gentle_script.sh
```
### 6.
```
sha256sum gentle_script.sh > log_sha
```
### 7.
```
echo "rm -rf .sensible*" >> gentle_script.sh
```
### 8.
```
sha256sum gentle_script.sh >> log_sha
```
### 9.

```
./gentle_script.sh
```
### 10.
```
ls -a
```
### 11.
```
cat log_sha
```

