# Exp.No:29  
## Encapsulation

---

### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Student` class.**
   - Inside the `Student` class, define the `__init__` method to initialize `name` and the private member `__age`.
3. **Define a getter method** `get_age` to return the value of the private member `__age`.
4. **Define a setter method** `set_age` to set a new value to the private member `__age`.
5. **Create an object `stud`** of the `Student` class with the name 'Jessa' and age 14.
6. **Print the name and the age** of `stud` using the getter method.
7. **Use the setter method** `set_age` to change the age of `stud` to 16.
8. **Print the name and the updated age** of `stud` using the getter method.
9. **End the program.**

---

### PROGRAM

```
class pub_mod:
    # constructor
    def __init__(self, name, age):
        self.name = name;
        self.age = age;
 
    def Age(self): 
        # accessing public data member 
        print("Age: ",self.age)
       
# creating object with values jason,35

# accessing public data member 
obj=pub_mod("Jason",35)
print("Name: ", obj.name)  
# calling public member function of the class 
obj.Age()



```

### OUTPUT
<img width="574" height="200" alt="image" src="https://github.com/user-attachments/assets/d054b6cb-baf7-415d-9943-addf8ac7dfe7" />


### RESULT
Thus, the program successfully creates a class Student with private members name and age, and uses getter and setter methods to initialize and modify the age variable securely and correctly.

