# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
#Developed By: KRISHNA KUMAR R
#Register Number: 212223230107
Unsorted=eval(input())
def selsort(Unsorted):
  n = len(Unsorted)
  for i in range(n-1):
    min_pos = i
    for j in range(i,n):
      if Unsorted[j]<Unsorted[min_pos]:
        Unsorted[j],Unsorted[min_pos] = Unsorted[min_pos],Unsorted[j]
  return Unsorted
print(selsort(Unsorted))
```
ii)	#Insertion Sort
```
#Developed By: KRISHNA KUMAR R
#Register Number: 212223230107
def Insertionsort(arr):
  for i in range(1,len(arr)):
    j = i
    while arr[j]<arr[j-1] and j>0:
      arr[j],arr[j-1] = arr[j-1], arr[j]
      j-=1
  return arr
arr = eval(input())
print(Insertionsort(arr))
```

## Output:

## selection sort 
![Screenshot 2024-04-05 121751](https://github.com/Krishna23013541/Sorting-Algorithms/assets/149557764/10faab8e-2565-424c-8f20-7052524b5239)

## insertion sort 
![Screenshot 2024-04-05 121815](https://github.com/Krishna23013541/Sorting-Algorithms/assets/149557764/3c32946f-01a8-41ef-8888-3b080cf34c94)

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
