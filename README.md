# Projet5G 

## In order to run this project you need to install the following dependencies : 

  in terminal write : 
   sudo apt-get install gcc g++ python python-dev mercurial bzr gdb valgrind gsl-bin libgsl0-dev libgsl0ldbl flex bison tcpdump sqlite sqlite3 libsqlite3-dev libxml2        libxml2-dev libgtk2.0-0 libgtk2.0-dev uncrustify doxygen graphviz imagemagick texlive texlive-latex-extra texlive-generic-extra texlive-generic-recommended texinfo      dia texlive texlive-latex-extra texlive-extra-utils texlive-generic-recommended texi2html python-pygraphviz python-kiwi python-pygoocanvas libgoocanvas-dev python-      pygccxml 
   
## Procced with : 

    cd 
    mkdir ns3 
    cd 
    
ns3 ## Installing NS-3 : 

    wget http://www.nsnam.org/release/ns-allinone-3.19.tar.bz2 
    tar xjf ns-allinone-3.19.tar.bz2 cd ns-allinone-3.19/ 

## Building and configuring the project : 
    
    ./build.py --enable-examples --enable-tests 
    ./waf -d debug --enable-examples --enable-tests configure 
## And finally to test everything : 
    
    ./test.py
