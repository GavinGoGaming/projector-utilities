# Projector for CSB

Install:

1. `cd projector-utilities` in the terminal
2. (You may need to "chmod +x csb-based-install.sh" if step 3 has "no permission")
3. `./csb-based-install.sh` in the same terminal

4. `projector` and wait for an error.
5. ctrl-click the line that contains "products.py" in the stacktrace
6. replace line 53 with:

```py
    ver: str = "0.0.0"
```

6. run `projector` again
7. accept license by typing `q` then `y` and clicking enter.
8. answer the questions to install!


Uninstall:
1. Copy the command from uninstall-projector-csb.sh in this repository and paste into terminal.
2. Click enter
