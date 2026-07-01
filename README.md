# Log Integrity & String Comparison Tool

## 🛡️ Defensive Overview
In cybersecurity, ensuring data integrity is critical. When analyzing two configuration files, security logs, or cryptographic outputs, standard visual inspection is inefficient. 

This C++ utility automates the process by performing a high-performance, byte-by-byte comparison between two strings (such as file hashes, network packet signatures, or log entries) to pinpoint the exact index of any discrepancy or unauthorized modification.

## 🚀 Key Features
* **Fast I/O Optimization:** Utilizes `ios_base::sync_with_stdio(false)` and `cin.tie(nullptr)` for optimized execution speed, making it suitable for processing large streams of log data.
* **Exact Mismatch Pinpointing:** Immediately returns the **1-based index** of the first mismatched character, allowing analysts to quickly locate tampered data.
* **Integrity Validation:** Outputs `YES` if both data streams are identical, confirming that no data tampering has occurred.

## 🛠️ Compilation and Execution
Compile the source code using any modern C++ compiler:
```bash
g++ -O3 main.cpp -o integrity_checker
./integrity_checker
