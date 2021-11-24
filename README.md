# 🔨 How To Build the Server with Makefile
[🇰🇷]  
Makefile을 사용했기 때문에 편하게 다음 명령어 하나로 실행파일인 driver, echocli, multisrv, timer 및 object file인 echolib.o를 생성할 수 있다.  

```$ make```

이를 통해 생성된 파일들은 testone을 실행할 때 사용된다.  
 
[Eng]  
Because of using Makefile, you can build execution files(driver, echocli, multisrv, timer) and object file(echolib.o) easily by entering command ```$ make```
<br/>

# ⚙ How To Execute testone
[🇰🇷]  
testone을 통해 test를 실행하기 위한 명령어는 다음과 같다.

```$ ./testone <thread 수> <client 수> <client 당 request 수>```

ex) thread는 최대 12, client는 11, client당 request수는 500으로 하고 싶다면 shell에 ``` $ ./testone 12 11 500 ``` 이라고 입력해야 한다.

[Eng]  
You can test easily by using ```testone``` file.  

```$ ./testone <num of threads> <num of clients> <num of requests per client>```