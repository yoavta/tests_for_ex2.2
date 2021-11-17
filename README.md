# tests_for_ex2.2 for Computer Archi
## How to:
- Go to terminal in __parent__ project directory. 


For example:
```bash
My project dir is : ~/university/computer structure/ex2
The terminal should be on : ~/university/computer structure
Like that : (yoav㉿kali-new)-[~/university/computer structure]
```

- Clone tests
```bash
git clone https://github.com/yoavta/tests_for_ex2.2.git
```

- Copy files to your project dir
```bash
cd tests_for_ex2.2  
mv output.txt test.c ../<name of your project dir>         # without the - <>
cd ../<name of your project dir> 
```

- Run the tests
```bash
 gcc -o result.out test.c ex2.s  -fPIE 
 ./result.out > result.txt
```

- Check the differences between your result output file - "result.txt", between expected output file - "output.txt"
```bash
diff output.txt result.txt
```

- if nothing has shown, your good. Else, it will print the differences between files. 
- if you are afraid, you can always check in text compare websites.


## Thanks to
- Thanks to the high school student who sat in front of me during class today and saw him do it.

## Disclaimer
- Own your responasabilty. I've just generated 250 random inputs and checked their correctness.
