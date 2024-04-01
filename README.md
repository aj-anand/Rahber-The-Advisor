# Rahber-The-Advisor
# Course Scheduler

## Overview
The Course Scheduler is a Python-based tool designed to help manage courses and their prerequisites effectively. It can detect circular dependencies, suggest an optimal learning path, and identify opportunities for parallel course enrollment.

## Features
- **Prerequisite Management**: Easily define prerequisites for each course.
- **Cycle Detection**: Automatically detects circular dependencies among courses.
- **Optimal Learning Path**: Calculates an optimal path for course completion based on prerequisites.
- **Parallel Enrollment**: Identifies courses that can be taken simultaneously.

## Getting Started
To use the Course Scheduler, follow these steps:

1. Initialize the scheduler with the total number of courses:
   ```python
   scheduler = CourseScheduler(total_courses=5)
