❯ time ./prpages ../../random_text_x4
6
./prpages ../../random_text_x4 
0.00s user 
0.00s system 
104% cpu 
0.008 total


❯ time (pr ../../random_text_x4 | awk 'END { print NR/66 }')
6
( pr ../../random_text_x4 | awk 'END { print NR/66 }'; )  
0.01s user 
0.00s system 
145% cpu 
0.011 total
