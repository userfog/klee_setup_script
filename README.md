# Klee Setup Script

[KLEE](https://klee.github.io/getting-started/) is a symbolic executor which can be used to verify certain properties about code. [Here](http://www.doc.ic.ac.uk/~cristic/papers/klee-osdi-08.pdf) is the paper originally published with KLEE.


This script automatically executes the KLEE getting started sequence, so that you can spend less time worrying about how to install KLEE and more time using it.

## System requirements
This script has only been tested on Ubuntu.

If you are interested in running KLEE on a different system please message me and I can make edits or submit changes on your own.


## Install 
```
mkdir klee_env
cd klee_env
git clone https://github.com/userfog/klee_setup_script.git
chmod 777 klee_setup.sh
./klee_setup.sh
```

