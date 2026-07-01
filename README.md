# Competitive Programming: String Comparison Algorithm

## 📝 Problem Description
This C++ program takes two strings, `s` and `t`, as input from the user. It iterates through both strings simultaneously to find the first position (1-indexed) where the characters differ. 

* If a mismatch is found, it immediately prints the 1-based index of that mismatch and terminates.
* If both strings are completely identical, it outputs `YES`.

## 🚀 Optimization Features
* `ios_base::sync_with_stdio(false);` and `cin.tie(nullptr);` are utilized to untie C++ streams from C standard streams, significantly speeding up Input/Output (I/O) operations for competitive programming platforms.

## 🛠️ How to Compile and Run
You can compile this code using any standard `g++` compiler:
```bash
g++ -O3 main.cpp -o main
./main
