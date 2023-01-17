# Terminal

## Comands

### 1

```console
dev $ echo 'hello, world!'
hello, world!
```

### 2

```console
dev $ pwd
/Users/len/dev
```

### 3 

```console
dev $ ls
practice.md 
```

#### i

```console
dev $ ls -a
.           ..          practice.md
```

#### ii

```console
dev $ ls -l
total 8
-rw-r--r--@ 1 len  staff  47 Jan 11 14:24 practice.md
```

### 4

```console
dev $ cd ~/
➜  ~
```

### 5

```console
~ $ cd dev
➜  dev
```

### 6

```console
dev $  mkdir root
➜  de $ v ls
practice.md root
➜  de $v root
➜  roo $t mkdir markdown text
➜  root $ ls
markdown text
➜  root $ markdown
➜  markdown $ touch file-0.md
➜  markdown $ ls
file-0.md
➜  markdown $ ..
➜  root $ text
➜  text $ touch file-0.txt file-1.md
➜  text $ ..
➜  root $ touch file-2.md file-1.txt file_2.txt file-0.tmp file-1.tmp file-2.tmp

➜  root $ ls
file-0.tmp file-1.tmp file-1.txt file-2.md  file-2.tmp file_2.txt markdown   text
```

### 7

```console
root $ cd root
root
```

### 8

```console
root $ mv text/file-1.md markdown
```

### 9

```console
root $ cp file-2.md  markdown
```

### 10

```console
root $ mv file_2.txt file-2.txt
```

### 11

```console
root $ cp *.txt text
```

### 12

```console
root $ rm *.tmp
```

### 13

```console
root $ rm *.md *.txt
```

### 14

```console
root $ ..
```

### 15

```console
dev $ ls -R root
markdown text

root/markdown:
file-0.md file-1.md file-2.md

root/text:
file-0.txt file-1.txt file-2.txt
```

#### i

```console
dev $ nano root.tree
```

### 16

```console
dev $ rm -r root
```

### 17

```console
dev $ cat root.tree
markdown text

root/markdown:
file-0.md file-1.md file-2.md

root/text:
file-0.txt file-1.txt file-2.txt
```

### 18

```console
dev $ head -3 ~/.zsh_history
: 1673248256:0;pycharm
: 1673248256:0;python
: 1673248256:0;print (hello)
```

### 19

```console
dev $ tail -3 ~/.zsh_history
: 1673426121:0;which zsh
: 1673426247:0;head -3 ~/.zsh_history
: 1673426312:0;tail -3 ~/.zsh_history
```

### 20

```console
dev $ grep world ~/.zsh_history
: 1673252286:0;grep world test.txt
: 1673254085:0;echo Hello, world!
: 1673421940:0;echo 'hello, world!'
: 1673426804:0;grep *world ~/.zsh_history
: 1673426843:0;grep world ~/zsh_history
: 1673426898:0;grep world ~/.zsh_history
```

### 21

```console
dev $ which zsh
/bin/zsh
```

### 22

```console
dev $ ping google.com
PING google.com (172.217.25.206): 56 data bytes
64 bytes from 172.217.25.206: icmp_seq=0 ttl=110 time=39.458 ms
64 bytes from 172.217.25.206: icmp_seq=1 ttl=110 time=48.802 ms
^C
--- google.com ping statistics ---
2 packets transmitted, 2 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 39.458/44.130/48.802/4.672 ms
```

### 23

```console
dev $ alias pg=' ping google.com '
```

## Operators

### 1

```console
dev $ mkdir dir1 && cd dir1
```

### 2

```console
dev $ ls ~ | grep Music
Music
```

### 3

```console
~ $ ls /dev > copy.exemple
~ $ cat copy.exemple
dir1
practice.md
root.tree
```

### 4 

```console
dev $ which whois >> copy.exemple
```

## Scripting 

### 1

```console
echo $ 'Hello, sweetie'
echo $ 'Please give me your name'
read $ name
echo $ $name >> names.txt
echo $ ''Welcome $name''
```

### 2

```console
echo $ 'Hi, i can calculate two numbers!'
echo $ 'Give me a first  number'
read $ num1
echo $ 'Give me second number'
read $ num2
echo $
let $ "sum=num1+num2"
echo $ 'The sum of those numbers =' $sum
let $ "multiply=num1*num2"
echo $ 'The multiplication of those numbers =' $multiply
```

### 3

#### 1

```console
echo $ 'Hello' $1'!'
echo $  $1 >> names.txt
echo $ 'Welcome and nice to meet you' $1'.'
```

#### 2

```console
echo $ 'Hello, today we will calculate two numbers.'
echo $
echo $ 'First we calculate sum.'
echo $ 'Number one is' $1 'and number two is' $2':'
let $ sum=$1+$2
echo $ 'The sum =' $sum
echo $
echo $ 'Then we will calculate multiplication of those numbers.'
let $  multiply=$1*$2
echo $ 'The multiplication =' $multiply
```

## Packages

### 1

```console
~/dev $ brew instal htop
```

### 2 

```console
~/dev $ brew uninstal htop
```

## Configuration

### 1

```console 
~/dev $ hw                                                                           
zsh: command not found: hw
~/dev $ nano ~/.zshrc
# Permanent alias - hello world.
 alias hw="echo hello world"
```

### 2

```console
 
```
