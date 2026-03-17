
# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
```
stack = []

# Add 4 elements to the stack
stack.append('a')
stack.append('b')
stack.append('c')
stack.append('d')

print('Initial stack: ' + str(stack))

# Print the top element
top = stack[-1]
print("\nElement at the top of the stack is .... ", top)

# Remove an element from the stack
stack.pop()

# Print the top element after popping
top = stack[-1]
print("\nAfter removing an element from the stack.")
print("\nElement at the top of the stack is .... ", top)
```

## Output
![image](https://github.com/user-attachments/assets/8434a478-581b-4169-86db-409e56830ba5)

## Result
    Thus the program allows inserting 3 elements from the user and then prints the **top element** of the stack was successfully executed.
