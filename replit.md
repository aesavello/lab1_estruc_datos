# C Lists & Stacks Lab

## Overview
This is a C programming lab (university exercise) focused on implementing List and Stack data structures. Students implement functions in `exercises.c` and run tests via `bash test.sh`.

## Project Structure
- `exercises.c` - Student implementation file (the only file students should modify)
- `arraylist.h` / `arraylist.c` - List TDA (Abstract Data Type) implementation
- `stack.h` - Stack TDA interface
- `test.c` - Test suite
- `test.sh` - Build and test script (compiles with gcc and runs tests)
- `log` - Auto-generated test log

## Running Tests
```bash
bash test.sh
```
This compiles `test.c` with gcc and runs the test binary, showing pass/fail results for each exercise.

## Workflow
- **Start application**: runs `bash test.sh` (console output)

## Notes
- No frontend or backend server — purely a C compilation project
- gcc 14.3.0 is available in the Nix environment
- Students must only modify `exercises.c`
