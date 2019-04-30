# cmocka_pg

cmockaの練習をするためにgit submodle addしたcmockaを利用できるようにした。

具体的にはCMakeLists.txtに以下のコードを追加して https://api.cmocka.org/ のサンプルコードをmain.cに書き込んだ。

```
add_subdirectory(cmocka)

target_link_libraries(cmocka_play cmocka)
```
