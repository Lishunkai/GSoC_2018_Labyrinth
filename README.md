# Labyrinth-GSoC-2018
This program solve the Labyrinth problem proposed by JdeRobot for GSoC 2018.It finds the largest pathway moving only between holes. The descriptions of the problem can be found at:
https://jderobot.org/store/jmplaza/uploads/gsoc/programming-test-c.pdf

## How to use
```
git clone ...
cd ...
mkdir build
cd build
cmake ..
make
./Labyrinth_GSoC2018 <the path to the input labyrinth>
```
The program will output the result as a txt file named 'Result.txt'.

## Example:
Input:
```
##.##.#
#..##.#
#.#####
#..####
##..###
###.###
```

Output:
```
10
##0##.#
#21##.#
#3#####
#45####
##67###
###8###
###9###
```

## Author
Shunkai Li, a senior student of Nankai University, China, and an incoming student of Peking University, China.
