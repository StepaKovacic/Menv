# Menv
Bash utility for managing python virtual environmnets. 

## Motivation
While coding in python, I used to have several virtual envs all over the pc with a variety of names so finding a specific one was pain leading me to create another env and another and another, yada yada yada. Here is simple code that puts all the virtual envs in one specific `dir` and lets you list them, check their pip moudles installed, deleting and so on. 

## Usage 
First, you propably need to put this code in .bashrc as a simple function, thats all. 

listing them
```
a -l
```

creating and starting `env` called `virtual-env`
```
a -c virtual-env
```

opening already available `env`
```
a -d virtual-env
```

deacitvating `env` (yes I am lazy)
```
deactivate
```
