# Initialising a 2D Array 📚

## Preface 🐶
Whats the fun in creating a 2D array if we can't store stuff in it? 😛
Here we will learn how to create a 2D array with values already present in it. This operation is called **initialisation**. 

## Getting Started 🎉

So before we learnt we could create an array with **2 rows** and **4 columns** by the following:
```
int my_array[2][4];
```

But lets say that we want to initialise some values to it, specifically:
- The integers `1,2,3,4`, in the **first row**
- The integers `5,6,7,8`, in the **second row**

To do that we would use the following initialisation:
```
int my_array[2][4] = {
  {1, 2, 3, 4}, // First row
  {5, 6, 7, 8} // Second row
};
```

If we were to add **another row**, it could look something like this!
```
int my_array[3][4] = {
  {1, 2, 3, 4}, // First row
  {5, 6, 7, 8}, // Second row
  {9, 10, 11, 12} // Third row
};
```

If we were to add **another column**, it could look something like this!
```
int my_array[2][5] = {
  {1, 2, 3, 4, 5}, // First row
  {6, 7, 8, 9, 10}, // Second row
};
```
Quite nice right?

### ✅ Now lets get started on **Accessing** elements in an array 😎 Continue [here](accessing.md)!
