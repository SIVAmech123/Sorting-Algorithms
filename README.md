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
developed by: sivakumar.R
reg no:23013501

def Insertionsort(arr):
    for i in range(1,len(arr)):
      j=i
      while arr[j]<arr[j-1] and j>0:
       arr[j], arr[j-1]=arr[j-1], arr[j]
       j-=1
    return arr
arr=eval(input())
print(Insertionsort(arr))







```
ii)	#Insertion Sort
```
def Insertionsort(arr):
  for i in range(1,len(arr)):
         j=i
         while arr[j]<arr[j-1] and j>0:
           arr[j], arr[j-1]=arr[j-1], arr[j]
           j-=1
  return arr
arr = eval(input())
print(Insertionsort(arr))





```

## Output:
<img width="599" alt="Screenshot 2024-04-06 225736" src="https://github.com/SIVAmech123/Sorting-Algorithms/assets/151629067/2a157f5d-f8ad-4764-9556-1d0cb1951a6c">


<img width="572" alt="Screenshot 2024-04-06 225743" src="https://github.com/SIVAmech123/Sorting-Algorithms/assets/151629067/664c4848-e0b1-400c-9736-81b00239fccf">


<img width="448" alt="Screenshot 2024-04-06 225756" src="https://github.com/SIVAmech123/Sorting-Algorithms/assets/151629067/610b69d0-1484-4f80-9f66-3d3cda2c22dc">



<img width="546" alt="Screenshot 2024-04-06 225805" src="https://github.com/SIVAmech123/Sorting-Algorithms/assets/151629067/51843594-a29c-4dcf-b3c4-07412ca2dac1">



## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
