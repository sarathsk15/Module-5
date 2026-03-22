# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```
#Reg.no: 212222063014
#Name: SARATH KUMAR.K
class Vehicles:
def init(self):
print('Vehicle created.')
def del(self):
print("Destructor called, vehicle deleted.")
obj = Fruits()
del obj
```

### OUTPUT
<img width="1267" height="281" alt="image" src="https://github.com/user-attachments/assets/f57e0f6d-6fa1-467d-adb7-e9376ad10710" />


### RESULT


Thus, the given python progran is implemented and executed sucessfully.
