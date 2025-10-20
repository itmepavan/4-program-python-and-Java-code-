✅ *Programming Basics – Part 4* ⚡

✅ *Functions & Scope* 💡👨‍💻

➊ *What is a Function?*  
A function is a *block of code* that performs a task and can be reused.

➋ *How to Define a Simple Function*

📍 *Python*  
```python
def greet():
    print("Hello!")
```

📍 *Java*  
```java
public static void greet() {
    System.out.println("Hello")

➌ *How to Call the Function*

📍 *Python:* `greet()`  
📍 *Java:* `greet();` (inside `main`)  

➍ *Function with Parameters*

📍 *Python*  
```python
def greet(name):
    print("Hello", name)
greet("Aman")
```

📍 *Java*  
```java
public static void greet(String name) {
    System.out.println("Hello " + name);
}
```

➎ *Function with Return Value*

📍 *Python*  
```python
def add(a, b):
    return a + b
```

📍 *Java*  
```java
public static int add(int a, int b) {
    return a + b;
}
``

➏ *Understanding Scope*

📍 *Python*  
```python
x = 10
def show():
    x = 5
    print(x)  # Local
show()
print(x)      # Global
```

📍 *Java / C++*  
```java
int x = 10;
void show() {
    int x = 5;  // Local
    System.out.println(x);
}



💬 *Tap ❤️ if you found this helpful!*
