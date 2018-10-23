Modified for Python 3.6.6

```
cd Linux
g++ LargeVis.cpp main.cpp -o LargeVis -lm -pthread -lgsl -lgslcblas -Ofast -march=native -ffast-math
python setup.py install
```
on MAC

```
cd Linux
g++ LargeVis.cpp main.cpp -o LargeVis -lm -pthread -lgsl -lgslcblas -Ofast -march=native -ffast-math -L/usr/local/lib -I/usr/local/include
python setup.py install
```
