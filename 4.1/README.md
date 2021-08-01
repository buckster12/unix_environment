
RUN:

$ egrep -f patterns /usr/share/dict/words

---

SOME TESTS:

$ egrep -f patterns /usr/share/dict/words  | grep ere
$ egrep -f patterns /usr/share/dict/words  | grep teet
$ egrep -f patterns /usr/share/dict/words  | grep tenet
