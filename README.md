Name: Daniel Abou ElEzz
Date: 22/9/2023

This C program provides a set of functions to perform various operations on arrays of unsigned char values. The following functions are included:

/*
1-void print_statistics(unsigned char arr[], int length, float *mean, float *median,
                unsigned char *max, unsigned char *min);
- This function takes an array of unsigned char values in addition to the length of the array and four declared pointers where we can store the median, mean, smallest number, and biggest number , all after being calculated using this function.

2-'int print_array(unsigned char arr[], int length);'
- This function takes an array of unsigned char values in addition to the length of the array and print it to the screen in addition to the length of the array.


3-int find_median(unsigned char arr[], int length);
- This function takes an array of unsighned char values and its length as argument, and returns the median of the elements in the array.


4-int find_mean(unsigned char arr[],int length);
- This function takes an array of unsighned char values and its length as argument, and returns the mean of the elements in the array.

5-int find_maximum(unsigned char arr[], int length);
- This function takes an array of unsighned char values and its length as argument, and returns the biggest number of the elements in the array

6-int find_minimum(unsigned char arr[], int length);
- This function takes an array of unsighned char values and its length as argument, and returns the smallest number of the elements in the array

7-void sort_array(unsigned char arr[], int length);
- This function takes an array of unsighned char values and its length as argument, and sorts the array in a descending manner


#Usage:
To use these functions in your C program, include the 'stats.h' header file and link it with your source code.

