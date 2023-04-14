# Accessing elements in a 2D Array 📚

## Preface 🐶
Whats the fun in storing elements in a 2D array if we can't access the elements? 😛
Here we will learn how to access the elements in a 2D array.

## Getting Started 🎉
To access an element in a 2D array you need **two** things!
- The **row** index
- The **column** index

With those two things we can access any element!

>Remember that indexes start at `0`, so the **first row** and **first column** will have indexes of `0`.
 
## Some Practice 🎯
Say we have the following array:
```
int my_array[2][4] = {
  {1, 2, 3, 4}, // First row
  {5, 6, 7, 8} // Second row
};
```

Let's see if we can identify the row and column indexes of each element! 

Try work it out yourself first, before clicking the dropdown answer :P

<details>
  <summary>Element 1</summary>
  > Element 1 is at [0, 0] !
</details>

<details>
  <summary>Element 2</summary>
  > Element 2 is at [0, 1] !
</details>

<details>
  <summary>Element 4</summary>
  > Element 4 is at [0, 3] !
</details>

<details>
  <summary>Element 5</summary>
  > Element 5 is at [1, 0] !
</details>

<details>
  <summary>Element 6</summary>
  > Element 6 is at [1, 1] !
</details>

<details>
  <summary>Element 8</summary>
  > Element 8 is at [1, 3] !
</details>

Well done! 

## Writing the code ✍️
So luckily writing the code to access an element is very similar to our thought process above - we need the **row and column indexes** of the element we want to access!

For example, if I wanted to access the element in the **first row** and **second column**, I would do the following:
```
int my_num = my_array[0][1];
```
This creates an integer variable called `my_num`, and assigns it the value of whatever element is stored at `my_array[0][1]`.

Pretty easy right? 

### ✅ Now lets get started on **Editing** an element 😎 Continue [here](editing.md)!