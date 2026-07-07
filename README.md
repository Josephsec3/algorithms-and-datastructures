# Binary Stream Processing in C++

## 📝 Description
This repository contains an efficient C++ solution designed to process a stream of binary characters (`0` and `1`). The algorithm filters the input stream by preserving all occurrences of `0` while identifying and tracking consecutive sequences of `1` without appending them to the final output string.

## 🚀 Optimization Techniques Used
* **`ios_base::sync_with_stdio(false);`**: Disables the synchronization between the C and C++ standard streams, significantly speeding up execution times for heavy I/O operations.
* **`cin.tie(nullptr);`**: Unties `cin` from `cout`, allowing for faster input processing which is crucial in competitive programming and high-performance applications.

## 🛠️ How to Compile and Run
Ensure you have a C++ compiler installed (like `g++`).

```bash
g++ -O3 main.cpp -o binary_processor
./binary_processor
