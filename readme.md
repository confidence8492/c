c語言標頭檔
1. 標準輸入輸出
   <stdio.h>: 提供標準輸入輸出功能，如 printf()、scanf()、fopen()、fclose() 等。
2. 標準函式庫
   <stdlib.h>: 包含通用的標準函式，如記憶體管理（malloc()、free()）、隨機數生成（rand()、srand()）等。
   <stddef.h>: 定義標準資料型態，如 size_t、NULL。
   <stdbool.h>: 支援布林值 true 和 false。
3. 字串與記憶體操作
   <string.h>: 字串處理和記憶體操作函式，如 strlen()、strcpy()、memcpy()。
   <strings.h>: 類似於 <string.h>，但提供一些非標準的函式，主要用於 POSIX 系統。
4. 數學運算
   <math.h>: 提供數學運算函式，如 sin()、cos()、sqrt()、pow() 等。
   <complex.h>: 提供複數運算相關的函式與資料型態。
   <tgmath.h>: 提供泛型數學函式，允許對不同數值型態使用相同的數學運算符號。
5. 時間與日期
   <time.h>: 處理時間和日期的函式，如 time()、clock()、difftime() 等。
6. 文件操作
   <fcntl.h>: 用於文件操作的 POSIX 標頭檔，定義了文件控制選項，如 open()、fcntl() 等。
   <unistd.h>: 提供對 Unix 系統呼叫的存取，如 read()、write()、close()，主要在 POSIX 系統上使用。
7. 錯誤處理
   <errno.h>: 定義錯誤代碼，如 errno 和一些常見錯誤碼（例如 ENOMEM、EIO）。
8. 資料型態與類型限制
   <stdint.h>: 定義固定長度的整數型態，如 int32_t、uint8_t。
   <inttypes.h>: 提供格式化輸出固定長度整數的宏定義。
   <limits.h>: 定義各種資料型態的限制，如 INT_MAX、CHAR_MIN。
   <float.h>: 定義浮點數型態的精度和範圍。
9. 巨集與標準定義
   <assert.h>: 提供斷言功能，用於調試，如 assert()。
   <ctype.h>: 提供字符分類與轉換的函式，如 isdigit()、isalpha()、toupper()。
   <stdarg.h>: 處理不定數目的函式引數，如 va_start()、va_arg()。
   <signal.h>: 用於處理訊號，如 signal()、raise()。
   <setjmp.h>: 提供跳躍控制函式，用於異常處理，如 setjmp()、longjmp()。
10. 多執行緒處理
    <pthread.h>: 提供 POSIX 標準的多執行緒程式庫（僅限於 POSIX 系統）。
11. 記憶體對齊與系統定義
    <sys/types.h>: 定義了一些基本的系統資料型態，主要用於 Unix 系統。
    <sys/stat.h>: 定義文件狀態的相關函式和資料結構，如 stat()。
    <sys/time.h>: 提供高精度的時間計算。
12. 位元操作
    <bitset.h>: 用於位元操作的函式（僅部分平台支援）。
13. 網路與通訊
    <netinet/in.h>: 定義了網路通訊協定的結構和常數，如 IP 地址結構。
    <arpa/inet.h>: 提供了將 IP 地址在二進位和字串格式之間轉換的函式。
    <sys/socket.h>: 提供套接字（socket）通訊的函式，如 socket()、bind()、connect() 等。
