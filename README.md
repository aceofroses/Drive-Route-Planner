# GPS-Planner-Project
Group project repository for Data Structures and Algorithms in Python. 


# GPS Route Planner
ABET-Centric Group Project – Data Structures and Algorithms (Python)

# Overview
This project is part of the ABET Project 1 requirement for the Data Structures and Algorithms course.
The goal is to design and develop a vehicle route planner that calculates the least-distance driving route between cities in Texas using algorithms such as Dijkstra and A*.

The system should:

- Consider cities with populations of 5,000 or more

- Track 10 or more planned trips

- Assign priorities to trips when only three vehicles are available

- Allow users to retrieve or review any trip when needed

# Objectives

- Apply core graph theory and shortest-path algorithms

- Implement efficient data structures like Graph, Heap, and Priority Queue

- Practice teamwork aligned with ABET student outcomes:

- Problem analysis

- Design and implementation

- Communication

- Ethical and professional conduct

- Team collaboration

# Project Structure
```
gps_route_planner/
│
├── main.py (Entry point for program execution)
│
├── core/ (Core data structure modules)
│ ├── graph.py
│ ├── priority_queue.py
│ ├── route_manager.py
│ └── init.py
│
├── algorithms/ (Algorithms implemented by sub-team)
│ ├── dijkstra.py
│ ├── astar.py
│ └── init.py
│
├── data/ (Input datasets - cities and routes)
│ ├── cities.csv
│ ├── routes.csv
│ └── test_cases/
│
├── tests/ (Unit and integration tests)
│ ├── test_graph.py
│ ├── test_dijkstra.py
│ ├── test_astar.py
│ ├── test_integration.py
│ └── init.py
│
└── docs/ (Documentation and deliverables)
├── requirements.md
├── design_overview.md
├── algorithms.md
└── testing_results.md
```

Team Roles
- Member 1 – Requirements & Data: Define constraints, collect datasets
- Member 2 – System Design: Core graph structure, architecture
- Member 3 – Algorithm A: Dijkstra shortest-path implementation
- Member 4 – Algorithm B: A* (A-Star) route planning implementation
- Member 5 – Integration & Ethics: Testing, documentation, presentation

# Getting Started

Prerequisites:

- Python 3.9 or higher

- Recommended editor: VS Code or JetBrains

# Installation Steps

## Clone this repository:
 - git clone https://github.com/
 - aceofroses/gps-route-planner.git
 - cd gps-route-planner

## Create and activate a virtual environment:
  - python -m venv venv
  - source venv/bin/activate (macOS/Linux)
  - venv\Scripts\activate (Windows)

## Install dependencies (if any are listed in requirements.txt):
  - pip install -r requirements.txt

  - Running the Program
  - Run the main program:
  - python main.py

## Execute tests:
  - python -m unittest discover tests

# Collaboration Workflow

Each member works on their assigned module.

Create a new branch for any feature:
git checkout -b feature/algorithm-implementation

Commit regularly and push changes:
git add .
git commit -m "Implemented Dijkstra algorithm"
git push origin feature/algorithm-implementation

Submit a Pull Request (PR) for review before merging to main.

# Testing and Validation

Each algorithm must be validated with at least three different city datasets.

Tests should verify:
• Correct route generation
• Proper priority assignment
• Handling of invalid or edge inputs

Performance comparisons between Dijkstra and A* will be recorded.

Ethics and Professionalism
All data, designs, and code in this repository are considered Intellectual Property (IP) under the ABET project agreement.
Team members must comply with the Non-Disclosure Agreement (NDA) and maintain academic integrity in all contributions.

License
This project is for educational use only and may not be redistributed or used commercially without team and instructor approval.

Credits
Developed collaboratively by:

Member 1 – Requirements, Data, Communication with Client

Member 2 – Design & Core System

Member 3 – Dijkstra Algorithm

Member 4 – A* Algorithm

Member 5 – Integration & Documentation

Tarleton State University
Department of Computer Science – Data Structures & Algorithms
