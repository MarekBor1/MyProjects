# SerwersProject

## Overview
SerwersProject is an educational project simulating a basic server-client architecture with focus on data packet handling, server management, and simple network operations.  
The system is split into:
- **NetSim (C++)**: simulates data packet flow and storage types in a network.
- **Serwery (Python)**: manages server instances with basic testing and validation.

Includes UML diagrams describing system structure and flow.

## Features
✅ C++ module for simulating packages and storage operations.  
✅ Python module for managing server objects.  
✅ Automated unit tests in Python using `pytest`.  
✅ UML diagrams of system architecture.

## Project Structure
Serwers_Project/
├── NetSim/
│ ├── package.cpp
│ ├── storage_types.cpp
│ └── types.hpp
├── Serwery/
│ ├── servers.py
│ ├── servers_test.py
│ └── PNG UML.png
├── docs/
│ ├── servers_plantuml.uml
│ └── servers_plantuml.txt
├── test/
│ └── test_servers.py

## Requirements
- C++11 compiler (for NetSim)
- Python 3.x
- pytest

## How to Run
### 1. Compile C++ module
```bash
cd NetSim
g++ -std=c++11 package.cpp storage_types.cpp -o netsim
./netsim
2. Run Python module
bash
Kopiuj
Edytuj
cd Serwery
python servers.py
3. Run tests
bash
Kopiuj
Edytuj
pytest servers_test.py
```
## Documentation
System diagrams can be found in /docs/servers_plantuml.uml and /Serwery/PNG UML.png.

## Author
Marek Borkowski
