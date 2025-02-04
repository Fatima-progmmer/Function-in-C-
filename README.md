
---

# Function in C  

This repository contains a C program demonstrating **functions** in C. Functions help in structuring code, improving reusability, and making programs more readable.  

## 🎥 Video Explanation  
I have also created a video explaining this program in detail. Watch it [here](your-video-link).  

## 📝 Program Overview  
- Defines a function to perform a specific task.  
- Calls the function from `main()` to execute the logic.  
- Demonstrates the concept of **function declaration, definition, and calling**.  

## 📜 Code Snippet  
```c
#include <stdio.h>

// Function declaration
int add(int a, int b);

int main() {
    int num1, num2, sum;

    printf("Enter two numbers: ");
    scanf("%d %d", &num1, &num2);

    // Function call
    sum = add(num1, num2);

    printf("Sum: %d\n", sum);

    return 0;
}

// Function definition
int add(int a, int b) {
    return a + b;
}
```  

## 🚀 How to Run  
### Option 1: Compile and Run the Code  
1. Clone this repository:  
   ```sh
   git clone https://github.com/Fatima-progmmer/Function-in-C-.git
   ```
2. Navigate to the directory:  
   ```sh
   cd Function-in-C-
   ```
3. Compile the program:  
   ```sh
   gcc function.c -o function
   ```
4. Run the executable:  
   ```sh
   ./function
   ```

### Option 2: Run the Pre-Compiled `.exe` File (Windows)  
1. Download the `function.exe` file from this repository.  
2. Double-click to run it.  
3. Follow the on-screen instructions.  

## 📌 Explanation  
- **Function Declaration** → `int add(int a, int b);`  
- **Function Call** → `sum = add(num1, num2);`  
- **Function Definition** → `int add(int a, int b) { return a + b; }`  

## 🤝 Contributing  
Feel free to fork this repository and contribute improvements!  

## 📜 License  
This project is open-source and free to use.  

---
