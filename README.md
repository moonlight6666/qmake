# qmake
An Erlang Multi-process compile tool 

Based on make.erl and mmake.erl 

Node: The thread number of CPU maybe the best worker num 

erl  -pa ../ebin  -s qmake all  -noshell -s init stop

starting bulid 100 files...

Recompile: ../src/test
.....
.....

When all compile success :
-------------------------------------------------------------
                       All success
           Built 502 files, used 2 minute, 6 second
-------------------------------------------------------------

When compile fail :
-------------------------------------------------------------
                    Error in file: mod_meta.erl                        
-------------------------------------------------------------
