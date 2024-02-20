# CSC245-Lab1
1. Create an array with 4 rows and 3 columns of zeros. Your results should look as below:
[[0. 0. 0.]
 [0. 0. 0.]
 [0. 0. 0.]
 [0. 0. 0.]]
2.Create an array of ones that has 3 rows and 4 columns. Your results should look as below:
[[1. 1. 1. 1.]
[1. 1. 1. 1.]
[1. 1. 1. 1.]]
3. Create an array containing integers 4 to 13 inclusive. Your results should look as below:
[4 5 6 7 8 9 10 11 12 13]
4. Create an array containing
[0., 1.5, 3., 4.5]
5. Create a 2 by 2 array containing '4' in each position. Your results should look like this:
[[4 4]
 [4 4]]
6
. Create 2 matrices:
i. Identity matrix of size 4
[[1. 0. 0. 0.]
 [0. 1. 0. 0.]
 [0. 0. 1. 0.]
 [0. 0. 0. 1.]]
ii. Diagonal matrix with [10,12] as the diagonals
[[10  0]
 [ 0 12]]
7. Create a 3 by 3 array with random floats in [0, 10]. Your answer may be different because it is random but it should look something like this:
[[6.3685612  0.61720883 8.93157783]
 [3.69927617 5.79879583 7.62145626]
 [7.21895112 4.02011535 4.48844787]]
8. Create a 3 by 3 array with random integers in [10, 20]. Your answer may be different because it is random but it should look something like this:
[[19 11 13]
 [10 11 13]
 [11 14 10]]
SLICING ARRAYS
1. Use this array for the following practice:
myArray = np.array([[11,12,13], [14,15,16], [17,18,19]])
a. Get a subarray of the first row and first 2 columns. Your results should look like this:
[11 12]
b. Change all elements in 1st and second row to 0. Your results should look like this:
[[ 0  0  0]
 [ 0  0  0]
 [17 18 19]]
2. Create an array that contains [0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20] and reverse the order.
RESHAPING
Use this array for the following practice:
myArray = np.array([[11,12,13], [14,15,16]])
Reshape the array to an array with 3 rows. Your results should look like this:
[[11 12]
 [13 14]
 [15 16]]
MATH
Use this array for the following practice:
myArray = np.arange(10)
1. Find the square of every number in array
2. Find the square root of every number in array
3. Multiply the square of each number in array with its respective square root
ADDING ELEMENTS
Use this array for the following practice:
myArray = np.array([[11,12,13], [14,15,16], [17,18,19]])
1. Add a new row of elements containing 20, 21 and 22
2. Add a new column of elements containing 30, 40 and 50
INSERTING ELEMENTS
1. Add 1 column of 1 to this array: myArray = np.zeros((2,2))
2. Add 2 rows of 2 to the answer from part 1
3. Remove the last column
4. Remove the last row
DELETING ELEMENTS
Remove the elements from the middle column of this array:
myArray = np.matrix([[1, 2, 3], [4, 5, 6], [9, 8, 7]])
Your codes should look like this:
[[1 3]
 [4 6]
 [9 7]]
TEST EXERCISE
Replace all odd numbers in the given array with -1
Start with:
exercise_1 = np.array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
Desired output:
[ 0, -1, 2, -1, 4, -1, 6, -1, 8, -1]
Convert a 1-D array into a 2-D array with 3 rows
Start with:
exercise_2 = np.array([0, 1, 2, 3, 4, 5, 6, 7, 8])
Desired output:
[[ 0, 1, 2]
[3, 4, 5]
[6, 7, 8]]
Add 202 to all the values in given array
Start with:
exercise_3 = np.arange(4).reshape(2,-1)
Desired output:
[[202, 203]
[204, 205]]
Generate a 1-D array of 10 random integers. Each integer should be a number between 30 and 40 (inclusive)
Sample of desired output:
[36, 30, 36, 38, 31, 35, 36, 30, 32, 34]
Find the positions of:
elements in x where its value is more than its corresponding element in y, and
elements in x where its value is equals to its corresponding element in y.
Start with these:
x = np.array([21, 64, 86, 22, 74, 55, 81, 79, 90, 89])
y = np.array([21, 7, 3, 45, 10, 29, 55, 4, 37, 18])
Desired output:
(array([1, 2, 4, 5, 6, 7, 8, 9]),) and (array([0]),)
Extract the first four columns of this 2-D array
Start with this:
exercise_6 = np.arange(100).reshape(5,-1)
Desired output:
[[ 0 1 2 3]
[20 21 22 23]
[40 41 42 43]
[60 61 62 63]
[80 81 82 83]]
