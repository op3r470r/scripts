# scripts
常用脚本集合

### rpg

生成随机密码（包含大小写字母和数字），可指定长度（默认为24）。

```console
op3r470r@:~$ rpg 10
jr7lWyomm5

op3r470r@:~$ rpg
gV54u8LdX0yyM4ChDW3Lh7Td
```



### moc

列出最常使用的命令。

```console
op3r470r@:~$ moc
  30 echo
  27 ssh
  23 ls
  23 cd
  17 sudo
  16 lsof
  15 cat
  12 ps
  12 man
  12 diff
```



### todo

显示、添加、删除和编辑待办事项。

```console
op3r470r@:~$ todo        # 列出待办事项
     1	item1
     2	item2
     
op3r470r@:~$ todo item3  # 添加待办事项
     1	item1
     2	item2
     3	item3

op3r470r@:~$ todo -d 3  # 删除第n个待办事项
     1	item1
     2	item2

op3r470r@:~$ todo -e    # 直接编辑待办事项
```

