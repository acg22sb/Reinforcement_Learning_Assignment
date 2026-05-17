# Reinforcement_Learning_Assignment
Assignment for my RL Module

## Run the student template and record all terminal output

From the repository root, run:

```bash
python -m pip install numpy matplotlib
python -u student_template.py 2>&1 | tee student_template_output.log
```

- `-u` forces unbuffered output so logs are written immediately.
- `2>&1` includes both errors and normal output in the log file.
- `tee` writes output to the terminal and to `student_template_output.log`.
