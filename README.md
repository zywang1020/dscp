# 114-2 DSCP Final Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zywang1020/dscp/blob/main/114dscp_finalproject.ipynb)

## Project Title

A Course-based Daily Schedule Planner for College Students

## Project Motivation

College students often need to manage courses, reports, exams, and study time at the same time. It can be difficult to plan study time early and avoid schedule conflicts.

This project uses course data exported from the university course system. Users can search courses, select the courses they are taking, enter report deadlines and exam dates, and generate a daily schedule plan automatically.

## How to Run

1. Click the **Open in Colab** button above.
2. Run the notebook cells in order.
3. Upload the course data file `export.xls`.
4. Search courses by keyword.
5. Enter selected course codes.
6. Enter report deadlines and exam dates for each course.
7. The system will generate a daily schedule plan.
8. Download `daily_schedule_output.csv`.

## Main Features

- Read course data from an Excel file
- Search courses by keyword
- Select courses by course code
- Check possible course schedule conflicts
- Enter report deadlines and exam dates
- Generate a daily study and report preparation plan
- Visualize daily planned workload
- Export the final daily schedule as a CSV file

## Tools

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

## Files

- `114dscp_finalproject.ipynb`: main project notebook
- `export.xls`: original course data
- `daily_schedule_output.csv`: generated daily schedule
- `my_course_schedule.csv`: selected course schedule

## Short Reflection

This project helped me practice reading Excel data, cleaning data with Pandas, parsing course time, creating visualizations, and designing a simple rule-based planner. Although it is only a prototype, it shows how data science skills can be used to support student time management.
