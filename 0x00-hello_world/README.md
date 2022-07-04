1. 0-preprocessor [gcc -E ${CFILE} -o c]
This script compiles a c file saved in the variable ${CFILE}. The [-E] option tellsthe compiler to stop at the preprocessor level. The [-o] option outputs the compiled file into a file named "c"
