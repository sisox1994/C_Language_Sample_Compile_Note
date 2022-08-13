編譯:$gcc -o app main.c

執行:$.\app 12 58 你 笨笨

輸出:

parameter (0) = .\app
parameter (1) = 12
parameter (2) = 58
parameter (3) = 你
parameter (4) = 笨笨



```c
#include <stdlib.h>
#include <stdio.h>

int main(int argc, char** argv)}{
    
    for(int i = 0; i < argc; i++){
        printf("參數(%d) = %s\n", i , argv[i] );        
    }
    system("PAUSE");
    return 0;
}


```

