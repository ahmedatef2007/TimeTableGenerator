
# Time Table Generator- Genetic Algorithm

## Overview
This Python script implements a genetic algorithm to generate class schedules for a university. The algorithm aims to optimize scheduling by considering various constraints such as room capacity, instructor availability, and avoiding time conflicts between classes.

## Features
- Entities: Includes classes for `Instructor`, `Room`, `TimeAvailable`, `Courses`, `Department`, and `Class`.
- Data Setup: Initializes data such as rooms, time availability, instructors, courses, and departments.
- Scheduling Logic: Generates schedules based on available data, assigning instructors, time slots, and rooms to classes.
- Population Generation: Creates a population of schedules, each representing a potential class schedule.
- Fitness Calculation: Determines the fitness of each schedule based on constraints like room capacity and avoiding conflicts.
- Evolution: Evolves the population over generations using genetic operators like crossover and mutation to improve schedules.
- Display: Provides functionality to print available data, generations, and schedules.

## Usage
1. Ensure you have Python installed on your system.
2. Run the `main.py` script to execute the genetic algorithm.
3. Adjust parameters like population size, crossover rate, and mutation rate as needed in the script.

## Files
- `main.py`: Entry point for running the genetic algorithm.
- `README.md`: This file, providing an overview of the project.
- `classes.py`: Defines classes for entities involved in scheduling.
- `genetic_algorithm.py`: Implements the genetic algorithm for generating schedules.
- `display.py`: Contains functions for displaying available data, generations, and schedules.

## Requirements
- Python 3.x
- Required libraries: `prettytable`
