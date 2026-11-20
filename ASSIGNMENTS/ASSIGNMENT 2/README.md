# DSA01-192511172-Assignment2 — Functions & Object-Oriented Programming in C++

- **Student Name:** Samrakshini G
- **Register Number:** 192511172
- **Course:** DSA0107 — Object Oriented Programming with C++ (CO2)
- **Submission Date:** 17/11/2026
- **Compiler & Version:** g++ 13 (`g++ -std=c++17 -Wall -Wextra`)

## Repository Structure
- `Q1/` — Call by Value, Reference & Pointer (Hostel Fee Concession Updater)
- `Q2/` — Return by Reference, Dangling Local Reference Warning & `std::vector` Reallocation Safety
- `Q3/` — Default Arguments & Function Overloading (Courier Charge Calculator)
- `Q4/` — Specifying a Class with an Array Inside It (Savings Account Mini-Statement)
- `Q5/` — Static Data Members, Static Member Functions & Arrays of Objects (College Bus Seat Tickets)
- `Q6/` — Friend Functions & `inline` Performance Benchmark (`-O0` vs `-O2` across 10M calls)
- `Q7/` — Day-4 Design Challenge: Diagnosing `O(k)` Array-Shifting Mini-Statement & Redesigning with an `O(1)` Circular Ring Buffer

## Compilation & Execution
Inside any task folder (`Q1` to `Q7`), compile and run using:
```bash
g++ -std=c++17 -Wall -Wextra <source_file>.cpp -o solution
./solution
```
For `Q6` optimisation benchmark:
```bash
g++ -std=c++17 -Wall -Wextra -O0 q6_train_planner_benchmark.cpp -o q6_O0 && ./q6_O0
g++ -std=c++17 -Wall -Wextra -O2 q6_train_planner_benchmark.cpp -o q6_O2 && ./q6_O2
```
