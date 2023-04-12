# Creating a 2D Array 🔧

## Preface 🐶
A 2D array is often referred to as an array of arrays, or a matrix! This is because it consist of rows and columns, and thus takes the shape of a matrix! 

![Array Example](/assets/1.png "img2")

## Getting Started 🎉
To create a 2D array in C, you will need to declare it using the following syntax:

```
<datatype> <arrayname> [row_size][col_size];
```

Where:
- `<datatype>` is the datatype of the array 
*(i.e. `int`, `char`, `bool`, etc...)*
- `<arrayname>` is the name of the array *(i.e. `my_array`)*
- `row_size` is the number of rows in the array
- `col_size` is the number of columns in the array

For example, to create a 2D array of integers with 2 rows and 4 columns, you would use the following declaration:

```
int my_array[2][4];
```

Pretty easy right? 

### ✅ Now lets get started on **Initialising** an array 😎 Continue [here](initialising.md)!