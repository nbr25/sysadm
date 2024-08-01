# Display System Processes in Human-Readable Format

This guide explains how to display system processes in a human-readable format using the `top` command and its alternative, `htop`.

## Using `top`

### Start `top` with Human-Readable Options

Run `top` with specific options to make the output more human-readable:

```bash
top -d 1 -o %CPU -c
```
# Use Interactive Commands in top

### Shift + E: Toggle between human-readable memory units (KB, MB, GB).

### Shift + M: Sort processes by memory usage.

### Shift + P: Sort processes by CPU usage.
### Shift + T: Sort processes by running time.
### c: Toggle between displaying the command name and full command line.
### 1: Toggle the display of each CPU core.
