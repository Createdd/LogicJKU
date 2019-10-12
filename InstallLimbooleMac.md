
## How to install limboole on Mac OS

1. go to JKU source [homepage](http://fmv.jku.at/limboole/) and download  `[ limboole-OSX (Mach-O 64-bit executable x86_64) ]`
2. make the file executable in the terminal with `chmod +x Downloads/limbooleOSX`
3. move it to your folder of choice
4. Create an example txt-file like [example](./exampleFile.txt)
5. in your terminal execute
```sh
./limbooleOSX -s exampleFile.txt
```
could be for example:

```sh
% SATISFIABLE formula (satisfying assignment follows)
a = 0
b = 0
```

(the fist argument is the path to the executable limboole )

for more info check the homepage