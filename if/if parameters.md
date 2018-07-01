# if参数的使用
[ -a FILE ] 如果 FILE 存在则为真。<br>
[ -b FILE ] 如果 FILE 存在且是一个块特殊文件则为真。<br>
[ -c FILE ] 如果 FILE 存在且是一个字特殊文件则为真。<br>
[ -d FILE ] 如果 FILE 存在且是一个目录则为真。<br>
[ -e FILE ] 如果 FILE 存在则为真。<br>
[ -f FILE ] 如果 FILE 存在且是一个普通文件则为真。<br>
[ -g FILE ] 如果 FILE 存在且已经设置了SGID则为真。<br>
[ -h FILE ] 如果 FILE 存在且是一个符号连接则为真。<br>
[ -k FILE ] 如果 FILE 存在且已经设置了粘制位则为真。<br>
[ -p FILE ] 如果 FILE 存在且是一个名字管道(F如果O)则为真。<br>
[ -r FILE ] 如果 FILE 存在且是可读的则为真。<br>
[ -s FILE ] 如果 FILE 存在且大小不为0则为真。<br>
[ -t FD ] 如果文件描述符 FD 打开且指向一个终端则为真。<br>
[ -u FILE ] 如果 FILE 存在且设置了SUID (set user ID)则为真。<br>
[ -w FILE ] 如果 FILE 如果 FILE 存在且是可写的则为真。<br>
[ -x FILE ] 如果 FILE 存在且是可执行的则为真。<br>
[ -O FILE ] 如果 FILE 存在且属有效用户ID则为真。<br>
[ -G FILE ] 如果 FILE 存在且属有效用户组则为真。<br>
[ -L FILE ] 如果 FILE 存在且是一个符号连接则为真。<br>
[ -N FILE ] 如果 FILE 存在 and has been mod如果ied since it was last read则为真。<br>
[ -S FILE ] 如果 FILE 存在且是一个套接字则为真。<br>
[ FILE1 -nt FILE2 ] 如果 FILE1 has been changed more recently than FILE2, or 如果 FILE1 exists and FILE2 does not则为真。<br>
[ FILE1 -ot FILE2 ] 如果 FILE1 比 FILE2 要老, 或者 FILE2 存在且 FILE1 不存在则为真。<br>
[ FILE1 -ef FILE2 ] 如果 FILE1 和 FILE2 指向相同的设备和节点号则为真。<br>
[ -o OPTIONNAME ] 如果 shell选项 “OPTIONNAME” 开启则为真。<br>
[ -z STRING ] “STRING” 的长度为零则为真。<br>
[ -n STRING ] or [ STRING ] “STRING” 的长度为非零 non-zero则为真。<br>
[ STRING1 == STRING2 ] 如果2个字符串相同。 “=” may be used instead of “==” for strict POSIX compliance则为真。<br>
[ STRING1 != STRING2 ] 如果字符串不相等则为真。<br>
[ STRING1 < STRING2 ] 如果 “STRING1” sorts before “STRING2” lexicographically in the current locale则为真。<br>
[ STRING1 > STRING2 ] 如果 “STRING1” sorts after “STRING2” lexicographically in the current locale则为真。<br>
[ ARG1 OP ARG2 ] “OP” is one of -eq, -ne, -lt, -le, -gt or -ge. These arithmetic binary operators return true if “ARG1” is equal to, not equal to, less than, less than or equal to, greater than, or greater than or equal to “ARG2”, respectively. “ARG1” and “ARG2” are integers.<br>
