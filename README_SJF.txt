All commands are to be entered from the directory containing the program files


COMPILE:
 g++ scheduler_sjf.cpp -std=c++11 -o scheduler_sjf  (entered at command line)
-must be compiled to c++ 11



RUN: 
-	./scheduler_sjf 0	(runs single processor scheduler)
-	./scheduler_sjf 1	(runs 4 processor scheduler)
-one input argument (optional) is a flag which tells the program whether to run single processor or multi-processor scheduler
-program defaults to single processor when no argument is supplied
-program always generates 50 processes