# Exp.No:30  
## COUNTER CLASS

---

### AIM  
To write a Python program to create a `Counter` class that can increment the value of a counter.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**

---

### PROGRAM

```
Reg no-212223020028
Name-Tharani devi.G
Write your code
class Counter:
    def __init__(self):
        self.current = 0

    def increment(self):
        self.current += 1

    def value(self):
        return self.current

    def reset(self):
        self.current = 0

counter = Counter()


#call the increment method three times
counter.increment()
counter.increment()
counter.increment()
print(counter.value())   
```

### OUTPUT
<img width="742" height="272" alt="Screenshot 2026-03-19 211834" src="https://github.com/user-attachments/assets/3f5ac7ca-928c-41ba-a72c-138767f364df" />


### RESULT
This program for Counter class which has one attribute called current which defaults to zero is successfully executed.
