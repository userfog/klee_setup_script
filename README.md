# Klee Setup Script

[KLEE](https://klee.github.io/getting-started/) is a symbolic executor which can be used to verify certain properties about code. [Here](http://www.doc.ic.ac.uk/~cristic/papers/klee-osdi-08.pdf) is the paper originally published with KLEE.


This script automatically executes the KLEE getting started sequence, so that you can spend less time worrying about how to install KLEE and more time using it.

## System requirements
This script has only been tested on Ubuntu.

If you are interested in running KLEE on a different system please message me and I can make edits or submit changes on your own.


## Install 
```
git clone https://github.com/userfog/klee_setup_script.git
cd klee_setup_script
./klee_setup.sh
```

## Edit ~/.bashrc
```
export C_INCLUDE_PATH=/usr/include/x86_64-linux-gnu
export CPLUS_INCLUDE_PATH=/usr/include/x86_64-linux-gnu
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/lib/x86_64-linux-gnu
export PATH=PATH_TO_KLEE_ENV/klee_env/llvm-gcc4.2-2.9-x86_64-linux/bin:$PATH
export PATH=PATH_TO_KLEE_ENV/klee_env/llvm-2.9/Release+Asserts/bin:$PATH
export PATH=PATH_TO_KLEE_ENV/klee_env/klee/Release+Asserts/bin:$PATH
```
