# ๐จ How To Build the Server with Makefile
[๐ฐ๐ท]  
Makefile์ ์ฌ์ฉํ๊ธฐ ๋๋ฌธ์ ํธํ๊ฒ ๋ค์ ๋ช๋ น์ด ํ๋๋ก ์คํํ์ผ์ธ driver, echocli, multisrv, timer ๋ฐ object file์ธ echolib.o๋ฅผ ์์ฑํ  ์ ์๋ค.  

```$ make```

์ด๋ฅผ ํตํด ์์ฑ๋ ํ์ผ๋ค์ testone์ ์คํํ  ๋ ์ฌ์ฉ๋๋ค.  
 
[Eng]  
Because of using Makefile, you can build execution files(driver, echocli, multisrv, timer) and object file(echolib.o) easily by entering command ```$ make```
<br/>

# โ How To Execute testone
[๐ฐ๐ท]  
testone์ ํตํด test๋ฅผ ์คํํ๊ธฐ ์ํ ๋ช๋ น์ด๋ ๋ค์๊ณผ ๊ฐ๋ค.

```$ ./testone <thread ์> <client ์> <client ๋น request ์>```

ex) thread๋ ์ต๋ 12, client๋ 11, client๋น request์๋ 500์ผ๋ก ํ๊ณ  ์ถ๋ค๋ฉด shell์ ``` $ ./testone 12 11 500 ``` ์ด๋ผ๊ณ  ์๋ ฅํด์ผ ํ๋ค.

[Eng]  
You can test easily by using ```testone``` file.  

```$ ./testone <num of threads> <num of clients> <num of requests per client>```