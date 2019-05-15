# C Vector
A simple library for dynamic sized arrays written in C programming language. Implementation is closely referenced to the `vector<T>` library present in C++'s STL.

## Usage instructions
- `#include cvector.h` in the client file(see `test.c` for reference) 
- compile cvector.h and cvector.c along with the client file(test.c in this case) using gcc or clang.  
Example: ``` gcc cvector.c cvector.h test.c -o foo ```
- run the executable  
Example: `./foo`

## Functions Implemented 
    TODO: Update with more information

1. **init()**  
    > Construct vector.  
    Prototype:
    `vector_int *vec_init(int size, int *status);`

2. **destroy()**
3. **assign()**
    > Assign vector content  
    Protoype: `int *assign(int position, int value, vector_int *v, int *status);`
    
4. **size()**
5. **capacity()**
6. **empty()**
7. **at()**  
    > Access element.  
    Prototype:
    `int *at(int position, vector_int *v, int *status);`

8. **front()**
9. **back()**
10. **data()**
11. **push_back()**  
    > Add element at the end.  
    Protoype:
    `int *push_back(int element, vector_int *v, int *status);`

12. **pop_back()**
13. **insert()**
14. **erase()**
15. **swap()**
16. **clear()**
17. **sort()**
18. **binary_search()**

## Contributors
- Aniket Kaulavkar 
- Mukund Kadlabal


#### Project is a WIP 
This project an implementation for our 4th semester `Design and Analysis of Algorithms` course project.
