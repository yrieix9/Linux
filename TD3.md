# TD3
## Exercise 1 :

### 1.
```
ls -l /
```

### 2.
```
ls -l / | grep "bin"
```

### 3.
```
ls -l / | grep "bin" | awk '{print $5}'
```

### 4.
```
stat -c '%y' /bin | awk '{split($1,a,"-"); print "Month: " a[2] ", Day: " a[3] ", Year: " a[1]}'
```

## Exercise 2 :

### 1.
```
curl https://en.wikipedia.org/wiki/List_of_cyberattacks > cyberattacks.txt
```
### 2.
```
grep "meta" cyberattacks.txt
```
### 3.
```
grep -oP "meta\s+\K\w+"  cyberattacks.txt
```
### 4.
```
grep -o "meta [[:alnum:]]*" cyberattacks.txt | awk '{print $2}'
```
### 5.
```
cat cyberattacks.txt | grep -A1 'mw-content-text' | grep -v 'mw-content-text'
```
