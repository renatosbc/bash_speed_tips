# bash_speed_tips
(https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
  
- Use bash own functions!!
```
time for i in {1..10000}; do echo $i+1000 | bc; done    -> 5s  
time for i in {1..10000}; do echo $(($i + 1000)); done  -> 0.5s  
```

- Use bash own functions!!
```
touch ./newfile   NO!  
>./newfile        YES!  
```
