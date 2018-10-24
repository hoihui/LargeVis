Modified for Python 3.6.6

```
cd Linux
g++ LargeVis.cpp main.cpp -o LargeVis -lm -pthread -lgsl -lgslcblas -Ofast -march=native -ffast-math
python setup.py install
```
on MAC:

change `lseek64` to `lseek` in Linux/ANNOY/annoylib.h

```
conda install gcc
cd Linux
g++ LargeVis.cpp main.cpp -o LargeVis -lm -pthread -lgsl -lgslcblas -Ofast -march=native -ffast-math -fpermissive
python setup.py install
```
