# BIT 2118 Scientific Computing Group Work

This repository contains the 19 practical Python programs supplied in the lecturer's group-work document (Tasks 2-20), organized for individual study and submission.

## Setup (Windows / VS Code)

1. Open this folder in VS Code.
2. Open Terminal → New Terminal.
3. Create a virtual environment:

```powershell
py -m venv .venv
```

4. Activate it:

```powershell
.\.venv\Scripts\Activate.ps1
```

5. Install the required libraries:

```powershell
python -m pip install -r requirements.txt
```

If PowerShell blocks activation, use `py -m pip install -r requirements.txt` without activation, or tell your tutor/assistant so the execution policy can be handled safely.

## Running a task

Run one program at a time from the project root, for example:

```powershell
python code/Task_02_numpy_arrays.py
```

Some tasks display Matplotlib graphs. Close the graph window to let the program finish.

## Required work for EACH task

1. Identify the inputs and mathematical operation.
2. Run the supplied program and record its actual output.
3. Change at least one input/parameter and explain the difference.
4. Explain the output and interpret any graph.
5. Modify the program for a different but related real-world case. Document assumptions, input data, output and interpretation.

Each task has a documentation template in its own folder. Fill it with your own run results. The Python source files are in `code/`.

## Individual GitHub submission

The lecturer requires each student to maintain an individual repository, not a shared group repository. After completing and checking the work, create a GitHub repository and upload this project. Submit your repository link and documentation through VLMS.
