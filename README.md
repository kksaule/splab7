# splab7 - lock and unlock

Chapter 28, homework (15 questions to answer). Good Luck!

### Q1
First let’s get ready to run `x86.py` with the flag `-p flag.s`. This code "implements" locking with a single memory flag. **Can you understand what the assembly code is trying to do?**  
---
The code uses `flag` variable as a lock. It acquires lock using _busy waiting_, increments `count` by `1` and releases the lock by setting `flag` to `0`.

### Q2

...

### Q15
