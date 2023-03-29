# TD4

## Exercise 1 :

### 1.
I created an account on Amazon AWS

### 2.
I created an EC2 server instance

### 3.
```
chmod 400 timskey.pem
ssh -i timskey.pem ec2-user@myIPadress
exit
```
### 4.
```
vim connect.sh
```
### 5.
```
chmod +x connect.sh
./connect.sh
```
### 6.
```
mv clesdeyrieix.pem .clesdeyrieix.pem
ssh -i .clesdeyrieix.pem ec2-user@myIPadress
./connect.sh
```

## Exercise 2 :

### 1.
```
touch test_from_remote_instance.txt
```

### 2.
```
touch test_from_remote_instance.txt
exit
```

### 3.
```
scp test_to_remote_instance.txt ec2-user@myIPadress
scp ec2-user@myIPadress:~/test_from_remote_instance.txt
```

### 4.
```
vim scp_to_remote_instance.sh 
scp $1 ec2-user@myIPadress : ~
vim scp_from_remote_instance.sh
scp ec2-user@myIPadress : ~/$1
```
