
$ grep '123\n' test1
$ grep '123' test1
123
$ grep "123\n" test1 c
$ nano test1
$ grep '123\n' test1

$ nano pattern
$ egrep -f pattern test1

$ nano pattern
$ egrep -f pattern test1
123

$ od -a test1
0000000    1   2   3  nl  nl   4   5   6  nl  nl   7   8   9  nl
0000016

$ grep '123\nl' test1
$
