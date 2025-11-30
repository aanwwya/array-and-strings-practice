#13. count how many numbers are odd
#given an array, count how many numbers are odd

#pseudocode:
#initialize counter = 0
#foe each num in arr
#if num % 2 != 0
#increase counter by 1
#return count  

def odd_nums(arr):
    counter = 0
    for a in arr:
        if a % 2 != 0:
            counter+=1
    return counter
print(odd_nums([2,5,7,8,11])) 

#output: 3

#14.count how many numbers are greater than the average 
# given an array of integers, 
# count how many numbers are greater than the array's avg

#pseudocode
# find the sum of all numbers
# compute average = sum / total numbers
# initialize counter = 0
# for each number in the array:
# if number > average:
# increase counter by 1
# return counter 

def count_greater_than_avg(arr):
    total = 0
    for a in arr:
        total += a
    avg = total / len(arr)

    counter = 0
    for a in arr:
        if a > avg:
            counter += 1
    return counter
print(count_greater_than_avg([2,4,6,8])) 

#output:2

# 15. negative numbers 
# given an array of integers, 
# count how many numbers are negative   

#pseudocode:
# initialize counter = 0
# for each number in the array:
# if number < 0:
# increase counter by 1
# return counter

def count_negative_nums(arr):
    counter = 0
    for a in arr:
        if a<0:
            counter+=1
    return counter
print(count_negative_nums([3,-1,0,-7,5,-2])) 

#output: 3

#16. count how many numbers in the array are greater than 10
#given an array of integers, 
# count how many numbers are greater than 10 

#pseudocode: 
# initialize count = 0
# for each number in the array:
# if the number is greater than 10
# increase count by 1
# return the count

def count_greater_than_10(arr): 
    counter = 0 
    for a in arr:
        if a>10:
            counter+=1
    return counter 
print(count_greater_than_10([4,12,9,25,3,18,7]))

#output: 3 

#17. find the product of all numbers in an array 
# given an array of intergers, 
# calculate the product of all elements in the array

# pseudocode:
# initialize product = 1
# for each num n in the array
# product = product * n
# return product

def array_product(arr):
    product = 1
    for a in arr:
        product = product * a
    return product
print(array_product([2,3,4]))
    
#output : 24

#18. count how many numbers are positive 
# given an array of integers, 
# count how many elements are greater than 0

#pseudocode:
# set counter = 0
# for each number n in the array:
# if n > 0:
# counter = counter + 1
# return counter


def positive_nums(arr):
    counter = 0
    for a in arr:
        if a>0:
            counter+=1
    return counter
print(positive_nums([4,-2,7,0,-5,10,3]))

#output: 4

#19. count how many numbers in the array are greater than 10
# given an array of integers, 
# count how many elements are greater than 10

#pseudocode:
# initialize counter = 0
# for each number n in the array:
# if n is greater than 10:
# increase counter by 1
# return counter 

def greater_than_10(arr):
    counter = 0
    for a in arr:
        if a>10:
            counter+=1
    return counter
print(greater_than_10([4, 12, 9, 25, 3, 18, 7]))

#output : 3

#20. find the difference between the largest 
# and smallest number in the array
# given an array of numbers, compute: largest − smallest

#pseudocode: 
# set largest = first element of the array
# set smallest = first element of the array

# for each number n in the array:
# if n > largest:
# update largest = n
# if n < smallest:
# update smallest = n

# difference = largest - smallest
# return difference

def difference(arr):
    largest=arr[0]
    smallest=arr[0]
    for a in arr:
        if a>largest:
            largest=a
        if a<smallest:
            smallest=a
    diff = largest-smallest
    return diff
print(difference([4,1,7,3,9])) 

#output: 8

#21.divisible by 2 or 3
#given an integers, count how 
# many numbers are divisible by 2 or 3

#pseudocode:
# initialize counter = 0
# for each number n in the array:
# if n is divisible by 2 or n is divisible by 3:
# increase counter by 1
# return counter 

def divisible_by_2_or_3(arr):
    counter = 0
    for a in arr:
        if a % 2 ==0 or a % 3==0:
            counter+=1
    return counter
print(divisible_by_2_or_3([2, 3, 4, 5, 6, 7, 9, 10]))
       
#output: 7

#22.find the sum of all odd numbers in the array
# given an array of integers,
# calculate the sum of all numbers that are odd

#pseudocode:
# set counter = 0
# for each number n in the array:
# if n is odd (n % 2 != 0):
#  add n to counter
# return counter


def sum_of_odd(arr):
    counter=0
    for a in arr:
        if a % 2 !=0:
          counter+= a
    return counter
print(sum_of_odd([1, 2, 3, 4, 5, 6, 7, 8, 9])) 

#output=sum:25 

#23. find the maximum even number in the array
# given an array of integers, 
# find the largest number that is even

#set max even = none
#for each num in arr:
#if n is even:
#if max even is none or n > max even
#return max even 

def max_even(arr):
    max_even = None  

    for n in arr:
        if n % 2 == 0:  
            if max_even is None or n > max_even:
                max_even = n

    return max_even
print(max_even([3,7,2,8,5,10,1,4]))

#output: 10

#24. find the minimum odd number in the array
# given an array of integers, 
# find the smallest number that is odd 

#pseudocode:
# set min_odd = none
# for each num in the array
# if n is not divisible by 2
# if min_odd is none or n<min odd:
# set min_odd = n
#return min_odd
 
def smallest_odd(arr):
    min_odd = None
    
    for n in arr:
        if n % 2 != 0:   # check if odd
            if min_odd is None or n < min_odd:
                min_odd = n
    return min_odd
print(smallest_odd([4,7,2,9,5]))

#output: 5


        